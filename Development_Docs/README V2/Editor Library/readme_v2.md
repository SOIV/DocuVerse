# DocuVerse
[한국어(KR)](readme_v2-ko.md) | [영어(EN)](readme_v2.md)

<div align="center">

![DocuVerse Logo](https://via.placeholder.com/200x200)

**Modern document system with powerful collaborative editing capabilities**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18.x-61DAFB.svg?logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933.svg?logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-5.x-47A248.svg?logo=mongodb&logoColor=white)](https://www.mongodb.com/)

</div>

## 🌟 Overview

DocuVerse is a comprehensive document management system built to enhance team collaboration and knowledge sharing. With its powerful and flexible editing capabilities, DocuVerse enables teams to create, organize, and maintain project documentation with advanced features not found in conventional wiki systems.

### Key Features

- **Advanced Document Editor** - Create rich, structured documents with powerful table support
- **Real-time Collaboration** - Edit documents simultaneously with team members
- **Version Control** - Track changes and revert to previous versions when needed
- **Hierarchical Organization** - Organize documents in a flexible, intuitive structure
- **Rich Media Support** - Embed images, diagrams, code blocks, and more
- **Powerful Search** - Find content quickly with Elasticsearch integration
- **Customizable Permissions** - Control access at document and category levels
- **Export & Backup** - Export documents to multiple formats (JSON, Markdown, PDF, HTML)

## 🚀 Getting Started

### Prerequisites

- Node.js 16.x or later
- MongoDB 5.x or later
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-organization/docuverse.git
   cd docuverse
   ```

2. Install dependencies:
   ```bash
   # Install server dependencies
   cd server
   npm install

   # Install client dependencies
   cd ../client
   npm install
   ```

3. Configure environment variables:
   ```bash
   # In server directory
   cp .env.example .env
   # Edit .env file with your configuration
   ```

4. Start development servers:
   ```bash
   # Start backend server
   cd server
   npm run dev

   # In another terminal, start frontend
   cd client
   npm run dev
   ```

5. Open your browser and navigate to http://localhost:3000

## 🏗️ Architecture

DocuVerse is built using a modern tech stack:

### Frontend
- **React.js** - UI library
- **Redux** - State management
- **ProseMirror/TipTap** - Base for our custom document editor
- **yjs** - Real-time collaboration data structures
- **Material-UI/Tailwind CSS** - UI components

### Backend
- **Node.js + Express** - Server framework
- **MongoDB** - Document database
- **Elasticsearch** - Full-text search
- **Socket.io** - Real-time communications
- **JWT** - Authentication

## 🖋️ Advanced Document Editor

Our editor is the heart of DocuVerse, providing a powerful yet intuitive document editing experience:

- **Comprehensive Markup Support** - Full support for markdown and customized markup syntax
- **Advanced Table Editor** - Create complex tables with merged cells, backgrounds, and nested content
- **Collapsible Sections** - Hide and reveal content sections
- **Document Structure** - Automatic table of contents generation
- **Drag and Drop** - Easily upload and insert images or files
- **Dual Mode** - Switch between visual and markup editing modes

## 👥 Collaboration Features

DocuVerse enables seamless team collaboration:

- **Real-time Co-editing** - Multiple users can edit the same document simultaneously
- **User Presence** - See who's currently viewing or editing a document
- **Cursor Tracking** - View other users' cursor positions
- **Change Highlighting** - Easily identify recent changes in documents
- **Comments & Discussions** - Discuss specific parts of documents

## 🔒 Security

- JWT-based authentication
- Granular permission controls
- Input validation and sanitization
- HTTPS encryption

## 🗺️ Roadmap

| Stage | Timeline | Focus |
|-------|----------|-------|
| MVP | 1-2 months | Basic markdown editor, document CRUD, user auth |
| Core | 2-3 months | Version control, NamuWiki editor, advanced search |
| Collaboration | 2-3 months | Real-time editing, notifications, comments |
| Advanced | 3-4 months | CSS theming, API development, performance optimization |

## 🤝 Contributing

We welcome contributions to DocuVerse! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to get started.

## 🌐 Community

Join our growing community:

<div align="center">
  <a href="https://discord.gg/docuverse">
    <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://x.com/DocuVerseApp">
    <img src="https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white" alt="X">
  </a>
  <a href="https://instagram.com/DocuVerseOfficial">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="https://youtube.com/c/DocuVerse">
    <img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white" alt="YouTube">
  </a>
</div>

## 📜 License

DocuVerse is released under the MIT License. See [LICENSE](LICENSE) file for details.

This DocuVerse project is licensed under the GPL-3.0 license - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For questions or support, please [open an issue](https://github.com/your-organization/docuverse/issues) or contact us at biz@docuverse-pj.com.
