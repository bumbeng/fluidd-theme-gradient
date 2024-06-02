## fluidd-theme-gradient

![fluidd-gradient](https://github.com/bumbeng/fluidd-theme-gradient/assets/111509593/a96c54ef-a30e-41a9-8e6b-f62462a3ed6c)


## How to install
- create a folder called .fluidd-theme in config section
- copy the downloaded files into this folder
- reload browser

## Logo change
- name an picture to logo.png
- put this image to .fluidd-theme
- insert these lines with `!! your url !!` of the logo.png file into custom.css

      .logo-wrapper {
            display: none !important;
        }
        .theme--dark .toolbar-logo {
            background-image: url(http://mainsailos.local/server/files/config/.fluidd-theme/sidebar-logo.png) !important;
            background-size: 48px !important;
            background-repeat: no-repeat !important;
            background-position: center !important;
        }
