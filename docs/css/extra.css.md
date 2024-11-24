my-project/
├── docs/
│   ├── index.md
│   ├── about.md
│   ├── css/
│   │   └── extra.css  # File CSS personalizzato
│   └── images/
│       └── sfondo-navbar-1920.png  # Immagine di sfondo
├── mkdocs.yml
└── ...

/* Modifica il colore di sfondo della navbar */
.md-header {
    background-image: url('/images/sfondo-navbar.png');
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
}