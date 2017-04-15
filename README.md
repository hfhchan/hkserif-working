# hkserif-working
Working Directory for Hong Kong Serif

JSON files in this directory are edited versions of the `glyf`s outputted by otfccdump (https://github.com/caryll/otfcc) from the 1.000 release of Source Han Serif (https://github.com/adobe-fonts/source-han-serif/).

The glyphs are based on merging and editing glyphs and character components.

## Hong Kong Serif
Hong Kong Serif aims to be a font derived from Source Han Serif that reflects the common conventions of and expections to Chinese serif fonts.  The glyphs adhere to what is expected by Hong Kong users, often referencing the forms in Hong Kong's commercial best-selling typefaces MSungHK and DFLiHei.  Where applicable, glyphs will be repurposed from CN, JP, KR or TW, with minor modifications, usually based on that order.

The glyphs intentionally deviates from *List of Graphemes of Commonly-Used Chinese Characters* as there is no evidence to suggest they represent the conventions of the majority of the population in Hong Kong. Numerous media have already reported on the discrepancies.

The glyphs also do not follow *Guidelines on Character Glyphs for Chinese Computer Systems*. The guideline imparts illogical designs because it was designed to unify the differences between handwriting and print to drastic extents.  This guideline is on most parts a clone of the printing character "reforms" carried by the Ministry of Education, ROC.  This is an inherently bad idea; imagine forcing typeface designers to use a single-storey *a* and *g* in a serif design.

## Current Status
This is the working directory of the font; only changed glyphs are currently available. For now, only the Regular weight is being worked on.  The hints and contour masks in the JSON are outdated.  Autohinting will be run on the outputted fonts when they are ready.

## Copyright
Source Han Serif is produced by Adobe and licensed under the SIL OPEN FONT LICENSE Version 1.1. Hong Kong Serif is not affiliated with Adobe.
