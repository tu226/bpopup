## bPopup - If you can't get it up - use bPopup

### DEMO: ###
http://dinbror.dk/bPopup

### API: ###
http://dinbror.dk/blog/bPopup

### DESCRIPTION: ###
bPopup is a lightweight jQuery modal popup plugin (only 1.34KB gzipped). It doesn't create or style your popup but provides you with all the logic like centering, modal overlay, events and more. It gives you a lot of opportunities to customize so it will fit your needs.

## CHANGELOG
### v 0.9.1 ###
* Bugfix: When moving an iframe through the DOM. IE9 will excecute the code in the iframe as many times as moves you make. Each time (but the last one) will  return udefined on Object, String, Array etc.
* Bugfix: When appending is false no overlay was created.
* Bugfix: Reordered onOpen callback trigger, moved it below the open call to prevent losing focus defined in the onOpen event. Thanks AsadR
