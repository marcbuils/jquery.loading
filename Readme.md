# Loading 
## Plugin jQuery qui affiche une image de chargement pendant une action
Loading est un plugin jQuery qui permet d'afficher une image de loading pendant le déroulement d'une action comme le chargement d'une requête ajax.

**Version courante:** 0.5
**Licence:** LGPL v3

###Options par défaut:
‘‘‘javascript	
$.loading.defaultOptions = {
    src:  'loading.gif',     // chemin de l'image
    alt:  'Loading...',      // texte 'alt' de l'image
    css:  {                  // css du div qui encadre l'image
        textAlign:  'center',
        display:    'inline'
    }
};
‘‘‘

###Exemple de modification des options par défaut:
‘‘‘javascript
$.loading.defaultOptions = $.extend({}, $.loading.defaultOptions, {
           src: 'images/mon_image.gif'
});
‘‘‘

###Utilisation:
‘‘‘	
.loading( );
/* ou */
.loading({ /* [options] */ });
‘‘‘

###Demo:
http://www.marcbuils.fr/2010/07/loading-plugin-jquery-qui-affiche-une.html
