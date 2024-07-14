# cr_epub

**cr_epub** is a powerful tool designed to create ebook files compatible with e-readers, mobile devices, and tablets. Whether you're an author, publisher, or just an ebook enthusiast, cr_epub makes it easy to generate high-quality EPUB files for a seamless reading experience across various devices.

## Features

- **Multi-Device Compatibility**: Create EPUB files that work on e-readers, mobile phones, and tablets.
- **User-Friendly Interface**: Simple and intuitive interface for easy ebook creation.
- **Customizable Options**: Various settings and customization options to tailor your ebooks to your preferences.
- **High-Quality Output**: Ensure your ebooks look great and provide a smooth reading experience.

## Installation

To install cr_epub, you can use the following command:

```bash
npm install cr_epub
```

## Usage

### Basic Usage

Here's a simple example of how to create an EPUB file using cr_epub:

```javascript
const cr_epub = require('cr_epub');

let ebook = new cr_epub({
    title: "My First Ebook",
    author: "Author Name",
    content: "This is the content of my first ebook."
});

ebook.save("my_first_ebook.epub");
```

### Advanced Usage

cr_epub offers advanced features for more complex projects. You can customize the metadata, add multiple chapters, and include images.

```javascript
const cr_epub = require('cr_epub');

let ebook = new cr_epub({
    title: "Advanced Ebook",
    author: "Author Name",
    language: "en",
    chapters: [
        {
            title: "Chapter 1",
            content: "This is the content of chapter 1."
        },
        {
            title: "Chapter 2",
            content: "This is the content of chapter 2."
        }
    ],
    images: [
        {
            path: "cover.jpg",
            type: "cover"
        }
    ]
});

ebook.save("advanced_ebook.epub");
```

## Documentation

For detailed documentation and additional features, please refer to the [cr_epub Documentation](#).

## Contributing

We welcome contributions from the community. If you'd like to contribute to cr_epub, please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name.
3. Make your changes and commit them with clear messages.
4. Submit a pull request to the main repository.

## License

cr_epub is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or need further assistance, please feel free to contact us at [tranthienthanh93@gmail.com](mailto:tranthienthanh93@gmail.com).
