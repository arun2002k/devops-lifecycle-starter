# devops-lifecycle-starter


devops-lifecycle-starter/
│
├── app.py                     # Python web application
├── requirements.txt           # Runtime dependencies
├── requirements-dev.txt       # Testing dependencies
├── Dockerfile                 # Instructions to build image
├── compose.yaml               # Run container locally
├── .dockerignore              # Exclude files from image
├── .gitignore                 # Exclude files from Git
│
├── tests/
│   └── test_app.py            # Automated application tests
│
├── scripts/
│   └── smoke-test.sh          # Post-deployment health check
│
├── .github/
│   └── workflows/
│       └── ci.yml             # Automated CI pipeline
│
└── README.md                  # Setup and project documentation
