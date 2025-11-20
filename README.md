# C/LAN Network Map

A web application which serves as a documentation to the physical and logical connection between network devices on campus grounds.

# Installation and Setup

## Prerequisites
- Node.js (version 22.17.1) which can be downloaded in [https://nodejs.org/en/download](https://nodejs.org/en/download)
- npm

## Development Setup

1. Clone the repository:
```bash
git clone https://github.com/KaiserAce/clan-network-map.git
cd clan-network-map
```

2. Install dependencies:
```bash
# For Node.js projects
npm install
```

3. Start the development server:
```bash
npm run dev
```
The application should now be accessible at [http://localhost:3000](http://localhost:3000).

## Deployment
### Building for Production
```bash
npm run build
```
This will generate optimized static files in the .next/ folder within the project folder.

```bash
npm run start
```
The application should now be accessible at [http://localhost:3000](http://localhost:3000).

