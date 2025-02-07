<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Painting with AI

Final project for the Building AI course

## Summary

This project explores the creation of an AI-powered tool that assists users in generating digital paintings. By leveraging machine learning models trained on a vast array of artistic styles and techniques, the tool enables both novice and experienced artists to create unique artworks with minimal effort.

## Background

The digital art space is rapidly expanding, yet many aspiring artists struggle with the technical skills required to translate their visions into digital formats. This project aims to democratize digital art creation by providing an intuitive AI-driven platform that simplifies the artistic process. My motivation stems from a passion for both technology and art, and a desire to make art creation accessible to everyone, regardless of their skill level.


* Problem 1: High barrier to entry for digital art creation.

* Problem 2: Limited access to diverse artistic styles and techniques.

* Problem 3: Time-consuming process of learning and applying complex digital art software.


## How is it used?

Users interact with the AI through a simple interface where they can select styles, color schemes, and basic shapes. The AI then generates a painting based on these inputs, which users can further refine. This tool is particularly useful in educational settings, therapeutic art sessions, and for professional artists looking for inspiration.

![](https://www.designbolts.com/wp-content/uploads/2014/04/Rainbow_Digital-art-Painting-by-sakimichan.jpg)
```
def generate_art(style, color_scheme, shapes):
    # AI model processes the inputs to generate art
    art_piece = AI_model(style, color_scheme, shapes)
    return art_piece
```


## Data sources and AI methods
The data for training the AI models comes from publicly available datasets of digital artworks, such as:

| Data Source	                              | Description                                                             |
| -------------------------------------------| ----------------------------------------------------------------------- |
| [WikiArt](https://www.wikiart.org/)       | A visual art encyclopedia with images of paintings from various artists.|
| [Google Art Project](https://artsandculture.google.com/)   | High-resolution images of artworks from museums around the world.|

The AI methods involve convolutional neural networks (CNNs) for style transfer and generative adversarial networks (GANs) for creating new artworks.

## Challenges

The project does not address the creation of physical art pieces, focusing solely on digital formats. Ethical considerations include ensuring the AI does not replicate copyrighted styles too closely and respects the originality of human artists.

## What next?

Future enhancements could include integrating virtual reality for immersive art creation experiences and expanding the AI's learning to include more contemporary and diverse art forms. Collaboration with artists and technologists would be essential for advancing this project.


## Acknowledgments

* Inspiration from the works of DeepArt.io and their style transfer technology.

* Dataset provided by WikiArt under public domain licenses.

* Special thanks to the open-source community for continuous support and resources.
