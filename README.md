# LiveDeCo: Decentralized Live Collaborator

## 🚀 Vision

Imagine a world where your documents are not just collaboratively edited in real-time, but also stored in a decentralized manner, giving you true ownership and control over your data. LiveDeCo turns this vision into reality by combining real-time collaboration with decentralized storage and advanced CRDT technology.

## 🌟 Project Highlights

- **Real-time Collaboration**: Smooth, Google Docs-like simultaneous editing
- **Decentralized Storage**: Secure, distributed document storage using BNB's Greenfield
- **Web3 Integration**: Seamless blockchain technology integration
- **CRDT Implementation**: Advanced conflict-free replicated data type for robust collaboration
- **P2P Communication**: Powered by Iroh network library for true decentralization

## 🏗 Project Structure

LiveDeCo consists of two main components:

1. **Editor**: A web-based frontend for real-time document editing
2. **CRDT-Automerge**: A Rust-based backend implementing CRDT for data synchronization

## 🛠 Technology Stack

### Editor (Frontend)
- Next.js, React, TypeScript
- Liveblocks for real-time collaboration
- BNB Greenfield for decentralized storage
- viem, wagmi, rainbowkit for blockchain interaction

### CRDT-Automerge (Backend)
- Rust programming language
- Iroh for P2P network communication
- Automerge for CRDT implementation

## 🔍 Key Features

1. **Simultaneous Editing**: Multiple users can edit documents in real-time
2. **Decentralized Storage**: Documents stored on BNB's Greenfield network
3. **Wallet Integration**: Secure access via Web3 wallets
4. **Version History**: Track changes and revert to previous versions
5. **Access Control**: Granular permissions for document sharing and editing
6. **P2P Synchronization**: Real-time data sync across multiple nodes
7. **CLI Interface**: Command-line operations for CRDT-Automerge

## 🚀 Getting Started

### Editor Setup
1. Navigate to the `editor` directory
2. Install dependencies: `npm install`
3. Set up environment variables (see `.env.example`)
4. Run the development server: `npm run dev`
5. Open `http://localhost:3000` in your browser

### CRDT-Automerge Setup
1. Navigate to the `crdt-automerge` directory
2. Build the project: `cargo build`
3. Run the first node: `cargo run`
4. For additional nodes: `cargo run -- --remote-id [first node ID]`

## 🔮 Future Roadmap

- Enhance CRDT implementation with Automerge for advanced synchronization
- Incorporate IROH for true peer-to-peer connections
- Improve user interface with GUI and web-based interface for CRDT-Automerge
- Implement end-to-end encryption and advanced user authentication
- Extend support for complex data structures (nested objects, arrays)
- Develop mobile and desktop applications for cross-platform support

## 🤝 Contributing

We welcome contributions to LiveDeCo! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get involved.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🏆 Acknowledgments

This project was initially developed as part of [Hackathon Name], aiming to revolutionize document editing by combining real-time collaboration with decentralized storage and advanced CRDT technology.
