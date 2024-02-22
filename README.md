<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
  <h3 align="center">Signage Display: Your One-Stop Digital Billboard Solution</h3>
  <p align="center">
    Design, create, and manage vibrant digital signs with ease.
    <br />
    <a href="https://empress.eco/"><strong>Explore the Website »</strong></a>
    <br />
    <br />
    <a href="https://github.com/empress-eco/signage_display/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/signage_display/issues">Request Feature</a>
  </p>
</div>

## About The Project

Signage Display is a robust, user-friendly tool designed to simplify your digital display board creation and management process. It caters to anyone who needs to create engaging, customizable digital signages, offering a streamlined solution to the traditionally cumbersome process of designing and displaying digital signages.

## Key Features

- **Rich Text Editor**: Unleash your creativity with a versatile text editor.
- **Customizable Images**: Enrich your signages with custom images.
- **Layout & Speed Customization**: Personalize the layout and transition speed to match your preferences.
- **Easy Installation**: Choose between effortless installation on the Empress Cloud or a straightforward local setup.

## Technical Stack and Setup Instructions

Signage Display operates on the Framework. 

### Installation

#### Install on Empress Cloud

1. Navigate to [Empress Cloud Dashboard- Sites](https://Empresscloud.com/dashboard/sites) and create a new site.
2. Choose "Select apps to install" and select "Signage Display".
3. Follow the new site wizard to complete the site setup.

#### Install Locally

1. [Set up Empress Bench](https://Empressframework.com/docs/v14/user/en/installation).
2. Navigate to the 'Empress-bench' directory you've created.
3. Run the following commands to set up a new site and install Signage Display:

```sh
bench new-site signage.localhost
bench get-app signage_display https://github.com/empress-eco/signage_display.git
bench --site signage.localhost install-app signage_display
bench start
```

4. Visit the site URL to complete the site initialization.

## Usage

#### Creating and Viewing Signages 

1. Search for 'Signage List' corresponding to the 'Signage' document type on your site.
2. Click the 'Add Signage' option.
3. Design the new signage by providing a title (mandatory), description, and display image.
4. Check the 'published' box to indicate if the new signage should be displayed on the signage display board.
5. Save the signage.
6. Visit your site URL followed by /display to view the signage slideshow on the display board.

## Contribution Guidelines

We value community contributions! Here's how you can help improve Signage Display:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the same terms.

We extend our heartfelt gratitude to the Empress Community for their foundational contributions to this project. Their innovation and dedication have been instrumental in shaping the essential tools that power this project. We are profoundly grateful for their pioneering work and ongoing support.