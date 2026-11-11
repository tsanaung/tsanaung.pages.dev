## Web to Deb Builder
A desktop application built with Electron to convert web applications into Debian package (.deb) installers for Linux distributions (such as Debian, Ubuntu, and Cutefish OS).  


## Features
Simple and intuitive desktop interface  <br>
Package web apps into native .deb installers  <br>
Built with Electron, HTML5, and vanilla JavaScript <br>

```bash
Project Structure
├── index.html          # Main application UI layout
├── renderer.js         # Frontend interactive logic
├── main.js             # Electron main process
├── package.json        # Dependencies and build configuration
├── package-lock.json   # Exact dependency lockfile
├── .gitignore          # Ignores build artifacts and node_modules
└── README.md           # Documentation
```

## Prerequisites
Ensure you have the following installed on your Linux system:  <br>
Node.js (v18 or newer recommended)  <br>
npm (comes with Node.js)  <br>
dpkg-deb / build tools (typically pre-installed on Debian/Ubuntu):  

```bash
 sudo apt update && sudo apt install dpkg binutils fakeroot -y 
```  

## Getting Started  

Clone the repository  

```bash
 git clone https://github.com/tsanaung/web_to_deb.git 
```  

```bash
 cd web_to_deb 
```  

Install dependencies  

```bash
 npm install 
```  

Run the application  

```bash
 npm start 
```  

## Building & Packaging
To create release bundles or Debian installers, run:  

```bash
 npm run build 
```  
(Check package.json for customized scripts and output directories)

## License MIT