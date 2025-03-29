# Ritease

## Setup and Running Instructions

### Prerequisites
Ensure you have the following installed on your machine:
- [Node.js]
- [Yarn]
- [Git]

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Hanorah/Ritease.git
   cd Ritease
   ```
2. Install dependencies:
   ```sh
   yarn install  
   # or
   npm install
   ```
3. Start the development server:
   ```sh
   yarn dev  
   # or
   npm run dev
   ```
4. Open your browser and visit `http://localhost:3000`

### Building for Production
To create a production build:
```sh
yarn build
# or
npm run build
```

To start the production server:
```sh
yarn start
# or
npm run start
```

## Libraries and Tools Used
### Main Framework:
- **Next.js**: Used for server-side rendering, routing, and performance optimizations.

### UI & Styling:
- **Tailwind CSS**: For fast and responsive styling.

### PDF Handling:
- **PDF-Lib**: Used to manipulate and annotate PDFs.

### State Management:
- **React Hooks (useState, useEffect)**: For managing component states.

## Challenges Faced & Solutions
1. **PDF Annotation Implementation**:
   - Challenge: Handling text placement and embedding fonts correctly.
   - Solution: Used `pdf-lib` to embed fonts and accurately position annotations.

2. **Responsive Design**:
   - Challenge: Ensuring a smooth experience on both mobile and desktop.
   - Solution: Used `flexbox` and `@media queries` in Tailwind CSS.

3. **Git Issues**:
   - Challenge: Pushing the initial commit and linking with GitHub.
   - Solution: Used `git push --set-upstream origin main` to set up the remote branch correctly.

## Features to Add if Given More Time
1. **Text Highlighting & Drawing Annotations**: Expanding beyond simple text annotations.
2. **Cloud Storage Integration**: Allow users to save and retrieve PDFs from a cloud service.
3. **User Authentication**: Implement authentication so users can manage their own annotated PDFs.
4. **Export to Different Formats**: Allow users to export PDFs to images or Word documents.

---
