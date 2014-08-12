Magento Mimi
============

A responsive Magento theme built off the RWD package (default theme). I am using Magento Community Edition 1.9 but this theme can be used for both Enterprise and Community.

This repo only contains the /app/design/ and /skin/ folders.

There are two branches, a master branch and a development branch. The master branch will always hold a production-ready version while the dev branch is for developing only.

[View the Demo Site](http://www.mimikimwebdeveloper.com/magento-mimi)

The Magento-issued sample data is loaded into the demo site in order to mimic the look of a fully-stocked store. I tried to change as little as possible in the admin so that you could potentially download this repo, load the sample data, and have an identical looking store up and running.

Any admin changes I made are documented below.

###Changes in the Admin Backend
Besides the obvious theme changes in *Config -> Design*, I have made the following changes in the admin:

- **Removed index.php from url:** in *Config -> Web -> Secure* and set "Use Secure URLs in Frontend" to "Yes"
- **Disabled payment methods:** in *Config -> Payment Methods*, disabled all payment methods but COD and added a note in the Instructions field about this being a demo store.

Feel free to download this and poke around the template files!

About the Author
-------------
[Mimi Kim](http://www.mimikimwebdeveloper.com) is a Magento-certified frontend web developer in Baltimore, MD.