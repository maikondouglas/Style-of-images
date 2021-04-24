# Style of Images

## You can make image modifications such as changing its color to black and white, resize it to any size, and add a logo in the bottom right corner of the image.

### Pre-requisites

Before you start, you will need to have the following tool installed on your machine:
[Git](https://git-scm.com). 
Besides this, it is good to have an editor to work with the code, such as [VSCode](https://code.visualstudio.com/)

### 🎲 Running the Back End (server)

```bash
# Install magi_magick
$ sudo apt-get install libmagickwand-dev

# Other option case not run
$ sudo apt-get install imagemagick

# To transform an image into black and white
$ ruby img_trans.rb exp.jpg to_black_and_white

# To resize an image to 800x800
$ ruby img_trans.rb exp.jpg resize="800x800"

# To add a logo to the image
$ ruby img_trans.rb exp.jpg watermark='logo.png'

# Joining commands
$ ruby img_trans.rb exp.jpg resize="800x800" to_black_and_white watermark='logo.png'
```