# fabiodeangelis
personal web site [here](https://fabiodeangelis.github.io/profile/)

## Import the google fonts

To embed a font, copy the code into the <head> of your html:

<link href="https://fonts.googleapis.com/css2?family=Lobster&display=swap" rel="stylesheet"> 

<style>
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
</style> 


CSS rules to specify families:

    font-family: 'Lobster', cursive;

# firefox cache

If you want Firefox to always download the latest files then you can change the doc frequency setting like this:

    type this into the address bar: about:config
    you will see a long list of settings with a "Search" bar at the top of the page
    type this into the Search: browser.cache.check_doc_frequency
    double click on the browser.cache.check_doc_frequency line to edit it
    change the value to: 1
    press OK to save the change

That's it.  Now the latest files and images will be download every time you request a page. You and your designer will finally be on the same page.


more info about the possible browser.cache.check_doc_frequency  settings:

3 - only check if it seems outdated (this should be standard)
2 - always use cached version
1 - always check for newer version
0 - check for newer version once per session








/*
@font-face {
  font-family: 'Alef';
  font-weight: 400;
  font-style: normal;
  src: url('http://fonts.gstatic.com/s/alef/v5/5jDodXBqLZ_uyhFtHw7V8A.eot');
  src: url('http://fonts.gstatic.com/s/alef/v5/5jDodXBqLZ_uyhFtHw7V8A.eot?#iefix') format('embedded-opentype'),
       local('Alef Regular'),
       local('tZeduU5-mwXNlHG2cx5KCvesZW2xOQ-xsNqO47m55DA.woff'),
       url('http://fonts.gstatic.com/s/alef/v5/VSH48mnkaaFYglCO-SehPvesZW2xOQ-xsNqO47m55DA.woff2') format('woff2'),
       url('http://fonts.gstatic.com/s/alef/v5/tZeduU5-mwXNlHG2cx5KCvesZW2xOQ-xsNqO47m55DA.woff') format('woff'),
       url('http://fonts.gstatic.com/s/alef/v5/gzq6OSepdeZ1VdycsVw6Vg.ttf') format('truetype'),
       url('http://fonts.gstatic.com/l/font?kit=FpiYdJYEktm6aYq7Zf_kvQ#Alef') format('svg');
}

@font-face {
  font-family: 'Lobster';
  font-weight: 400;
  font-style: normal;
  src: url('http://fonts.gstatic.com/s/lobster/v12/RbZDm27knEncUX6lPsjRBg.eot');
  src: url('http://fonts.gstatic.com/s/lobster/v12/RbZDm27knEncUX6lPsjRBg.eot?#iefix') format('embedded-opentype'),
       local('Lobster'),
       local('Lobster-regular'),
       url('http://fonts.gstatic.com/s/lobster/v12/G6-OYdAAwU5fSlE7MlBvhQLUuEpTyoUstqEm5AMlJo4.woff2') format('woff2'),
       url('http://fonts.gstatic.com/s/lobster/v12/NIaFDq6p6eLpSvtV2DTNDQLUuEpTyoUstqEm5AMlJo4.woff') format('woff'),
       url('http://fonts.gstatic.com/s/lobster/v12/TSDaXhyJuDJ-NBU0popSWA.ttf') format('truetype'),
       url('http://fonts.gstatic.com/l/font?kit=j6oWj_2FuMvwWoXYXnyDeA#Lobster') format('svg');
}
*/
