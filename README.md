# raidionics-ohif-plugin

## 13.1 Installation
### 13.1.1 Install nodejs
* Go to https://nodejs.org/en and download the archive
* Follow the installation guide from https://github.com/nodejs/help/wiki/Installation

### 1.13.2 Install yarn
* npm install --global yarn
* yarn config set workspaces-experimental true

## 13.2 Installing Orthanc (DICOMWeb)

## 13.2 Running the OHIF Viewer
git clone https://github.com/OHIF/Viewers.git
cd Viewers
yarn install
yarn run dev

## 13.3 Plugins
* Create a new extension from scratch: yarn run cli create-extension
* Link existing extension: yarn run cli link-extension /path/to/extension

## 13.4 Modes
* yarn run cli create-extension
* yarn run cli link-extension /path/to/extension

## 13.5 Modes
* yarn run cli create-mode
* yarn run cli link-mode /path/to/mode
