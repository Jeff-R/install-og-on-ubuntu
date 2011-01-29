install_og is a set of scripts to install a development instance of [opengovernment.org](https://github.com/opengovernment/opengovernment) on Ubuntu. The scripts should work with just a bit of adjusting on Debian.

Why? It takes a number of steps to set up the site. And it bugs me to type the same things over and over. And I'm hoping that this will help other people install the site quickly.

To use the scripts:

Edit the file run_as_root. You will have to replace the defaults there with your own valuers.

And then, as root (imagine that), from the script's directory, run it.

Once it's done, you will need to make the config/database.yml and config/api_keys.yml files. There are sample files in config/ to get you going.

Then you should be ready to install data and get going.
