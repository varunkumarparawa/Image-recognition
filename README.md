🛒 Product Image Recognition & Inventory Automation
YOLOv8 • SQLite • Gradio • AI-Based Product Detection System
📌 Overview

This project is an AI-powered Product Recognition System designed to automate inventory management by detecting products from uploaded images. It identifies items using a trained YOLO model, retrieves metadata from a database, logs detection history, and supports full product management through a user-friendly interface.

The system reduces manual data entry, improves accuracy, and speeds up product cataloging for retail, warehouse, and e-commerce industries.

🚀 Features
🔍 Automatic Product Detection

Detects objects in uploaded images using YOLOv8

Draws bounding boxes and displays detection confidence

🧠 Smart Product Identification

Matches detected labels with the SQLite database

Fetches Name, Category, SKU, Brand

🗃 Product Database Management

Add new products

View all existing products

Delete items by SKU

🪪 Detection Confidence Check

Confidence ≥ 70% → Verified

Confidence < 70% → Low Confidence – Review Needed

📜 Detection History Logging

Saves timestamp, confidence, and status of each detection

🖥 Interactive Front UI (Gradio)

Tabbed interface:

Image Detection

Product Management

View Detection History

🛠️ Tech Stack
Component	Technology
Object Detection	YOLOv8
Front-end UI	Gradio
Database	SQLite
Programming Language	Python
Image Processing	Pillow, NumPy
📁 Project Structure
📦 Product-Image-Recognition
│
├── product_db.sqlite       # SQLite database file
├── yolov8n.pt              # YOLO model file
├── notebook.ipynb          # Google Colab runtime notebook
├── README.md               # Documentation
└── sample_images/          # Test images

▶️ Run in Google Colab
Step 1 – Install Dependencies
!pip install ultralytics gradio pillow

Step 2 – Upload Files

yolov8n.pt

product_db.sqlite

Step 3 – Launch App
demo.launch()

📸 Demo Workflow
Phase	Functionality
Phase 1	Image receiving test
Phase 2	YOLO detection
Phase 3	Product identification
Phase 4	SQLite integration
Phase 5	Admin panel & product CRUD
Phase 6	History logging & confidence scoring
Final	Complete integrated UI
🎯 Use Cases

Smart retail checkout

Inventory management automation

Stock verification system

Digital catalog creation

📌 Future Enhancements

Custom product dataset training

Real-time camera-based detection

Cloud DB (MySQL)

Barcode / QR code scanner support

📄 License

MIT License

✨ Developed by

Varun Kumar
AI Inventory Automation & Product Recognition Developer
