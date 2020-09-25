Opgave (The Grand Finale)
Denne opgave skal laves og afleveres inden 8/10 sammen med SASS opgaven
Der er mulighed for hjælp via Zoom d. 29/9 

I grupper på 2-3 personer skal i 

I skal lave en hjemmeside for jeres virksomhed der levere webdesign/UI/UX, udvikling og/eller hosting af websites (I vælger fokusområde)
Design en responsiv mobile-first hjemmeside i Adobe XD (LÆS grundigt videre da der er lavet en kickstart XD)
Alle gruppemedlemmer skal arbejde på den og have lavet ca lige meget indhold
Hjemmesiden skal have minimum 2 breakpoints så den tilpasser sig mobil, tablet og computer
Hjemmesiden skal laves med Bootstraps framework
Brug så vidt muligt kun Bootstrap klasser til styling
Undersøg altid til bunds om en given ting kan laves med Bootstrap også selvom det virker nemmere bare at skrive koden selv
Målet med øvelsen er at blive god til Bootstrap, og på sigt kunne udvikle meget hurtigere, men i starten vil nogle ting tage længere tid
I skal bruge Git/Github og alle i gruppen skal bidrage med commits

Der skal anvendes Gulp og SCSS (ingen rene css filer)
Vær smart ved brug af SCSS (de steder hvor Bootstrap ikke kan bruges)
Brug igen tid på at undersøge om en given ting kan løses ved brug at SCSS funktioner
I starten vil du bruge længere tid, men efterhånden som du bliver bedre til SCSS, vil du opleve at du bliver mere effektiv
Opgavens fokus er at i bliver bekendt med Bootstrap som framework, samtidig med at i vedligeholder (og udvikler) jeres evner i de forrige ugers emner.

Derfor får i et forspring på designet som i kan downloade herunder.
XD filen er baseret på Bootstraps 12 kolonners grid
Designet er sterilt og anonymt, så brug gerne noget tid på at give designet jeres eget præg.





// Extra small devices (portrait phones, less than 576px)
// No media query for `xs` since this is the default in Bootstrap

// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }



// No media query necessary for xs breakpoint as it's effectively `@media (min-width: 0) { ... }`
@include media-breakpoint-up(sm) { ... }
@include media-breakpoint-up(md) { ... }
@include media-breakpoint-up(lg) { ... }
@include media-breakpoint-up(xl) { ... }

// Example: Hide starting at `min-width: 0`, and then show at the `sm` breakpoint
.custom-class {
  display: none;
}
@include media-breakpoint-up(sm) {
  .custom-class {
    display: block;
  }
}




// Extra small devices (portrait phones, less than 576px)
@media (max-width: 575.98px) { ... }

// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) and (max-width: 767.98px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) and (max-width: 991.98px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) and (max-width: 1199.98px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }




