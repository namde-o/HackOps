# HackOps
Hackathon 2025 project – built with caffeine, code, and chaos.
Mini e-commerce platform with frontend, backend, and API integration.

HackOps-Ecommerce/
│
├── frontend/                     # Client-side code
│   ├── index.html                 # Home/product listing
│   ├── product.html               # Product detail page
│   ├── cart.html                  # Shopping cart page
│   ├── styles.css                 # Styles
│   ├── script.js                  # Handles API calls & UI logic
│   └── assets/                    # Images/icons
│
├── backend/                       # Server-side logic
│   ├── app.py                     # Flask app / main server file
│   ├── routes/                    # API route handlers
│   │   ├── products.py
│   │   ├── cart.py
│   │   └── auth.py
│   ├── models/                    # Database models
│   │   ├── product_model.py
│   │   ├── user_model.py
│   │   └── order_model.py
│   ├── utils/                      # Helper functions
│   │   └── db_connect.py
│   └── requirements.txt            # Python dependencies
│
├── database/                       # DB schema & data
│   ├── schema.sql                   # Create tables
│   ├── seed_data.sql                 # Insert sample products/users
│   └── db.sqlite                     # SQLite DB file (optional for dev)
│
├── ai/                              # AI chatbot & recommendations
│   ├── chatbot.py                    # Simple chatbot logic
│   └── recommender.py                # Product recommendation script
│
├── docs/                            # Documentation
│   ├── API_endpoints.md              # All API routes & usage
│   └── project_plan.md               # Project overview & team roles
│
├── .gitignore                       # Ignore unnecessary files
├── README.md                        # Project description & setup guide
└── LICENSE                          # Open-source license (MIT recommended)

