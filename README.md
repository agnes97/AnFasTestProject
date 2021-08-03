# AnFas Test Project

## DEV GUIDE

- instal dependencies for Sass with `npm install`
- run Sass transpilation with `npx sass --watch ./styles.scss ./styles.css`

## NOTES

#### JAK DLOUHO VÁM TO TRVALO?

Samotné kódování mi v prvním dni zabralo přibližně 5 hodin, plus hodinka na setup (nový projekt, git, npm, Sass) a ve druhém jsem věnovala něco přes hodinu finálním úpravám a lehkému refactoringu. V historii commitů je možné sledovat průběh vývoje. Myslím si, že by to bylo méně, kdybych si přitom neověřovala některé postupy v Sass, který jsem dosud nepoužívala příliš často.

#### ZMĚNY OPROTI ZADÁNÍ

1. Místo pixelů jsem použila relativní jednotky jako `%` a `em` (samozřejmě mimo například rámečků). Je to z toho důvodu, že se mi vždy osvědčily při tvorbě responsivního designu. Moc se mi líbí [vysvětlení z portálu Vzhůru dolů](https://www.vzhurudolu.cz/prirucka/jednotky).

1. Přidala jsem několik `:hover` efektů a animaci k video galerii, aby byl web více interaktivní.

1. Dle zadání předpokládám, že jsem obrázky nemusela rozmazávat, ale inspirovalo mě to a s každým z nich jsem tak pro ukázku pomocí CSS udělala něco trochu jiného. :wink:

1. Všechny obrázky jsem stáhla z [Pixabay](https://pixabay.com/) a optimalizovala je pomocí [TinyJPG](https://tinyjpg.com).

1. Použité ikony se lehce liší od zadání, přizpůsobila jsem se své oblíbené knihovně [FontAwesome](https://fontawesome.com/v5.15/icons), která mi umožňuje s nimi jednat jako s fontem.
