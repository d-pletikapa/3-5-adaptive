# 3-5-adaptive

@media (max-width:1280px) and (min-width:1000px) {
body {
background-color: red;
}
}

@media (orientation: portrait) {
body {
background-color: green;
}
}

@media (max-width:320px)  {
body {
display: none;
}
}

@media /* Variants */ print screen all /* Variants */  {
body {
display: none;
}
}

/*Desktop first*/
/*1366 ~ (1200)*/
/*1024 ~ (1000)*/
/*768*/
/*480*/

/*Mobile first*/
/*480 (540)*/
/*768*/
/*1000*/
/*1366*/
