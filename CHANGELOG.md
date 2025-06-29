# Changelog

## Recent Changes

### [Unreleased]

### [0.6] - Auto-merged
- **Auto-merge**: Resolved conflicts (commit: 4edbc43)
- **Project Status**: Project moved to other repositories (gitlab, bitbucket) (commit: 73580d4)
- **Documentation**: Updated public repository locations (commit: 2c43037)

### Features & Improvements
- **Error Handling**: Added more error codes (commit: d86da8a)
- **Build System**: Switched build script from deprecated distutils to recommended setuptools (commit: db9faba)
- **Field Initialization**: Ensured fields are always initialized (commit: 9bd9f3c)
- **Security**: Changed URL to HTTPS (commit: 2b24ee1)
- **Version**: Bumped version to 0.6 (commit: 94c72f4)
- **API Enhancement**: Enhanced options for FT.ENC_TAG/FT.IMAGE_TAG and added FT.DEC_TAG to match HarfPy functionality (commit: 923ca62)
- **Code Style**: Replaced all triply-quoted strings with multiline singly-quoted string literals (commit: f79dd5f)
- **Distribution**: Added config for uploading to PyPI (commit: 0c30a4a)

### Earlier Changes
- **Documentation**: Added link to backup repository (commit: 02264cd)
- **Outline Sources**: Added another source of Outline objects (commit: 8d8d81f)
- **API Convenience**: Allowed defaulting Library args where possible (commit: de9509f)
- **Prototypes**: Filled in more prototypes (commits: 467e96b, d08b959)
- **Memory Management**: Improved handling of SfntName memory ownership (commit: 2564aa9)
- **Error Handling**: More graceful handling of possible Library cleanup conditions (commit: b468f76)
- **API Enhancement**: Added Face.new and Face.find as alternatives to Library methods, allowing use without mentioning libraries (commit: efc690c)
- **Library Management**: Allowed using default Library instance everywhere a Library is expected (commit: 97fb91b)