# Husinka (složka hlazeni)

Statický web: jediný soubor `index.html` v kořeni repozitáře, bez buildu. Repozitář na GitHubu se jmenuje `pohlazeni`.

## Jak se synchronizuje (GitHub → Vercel)

- Složka `C:\Users\Ilona\Desktop\hlazeni` je git repozitář napojený na GitHub `inkvizithorr/pohlazeni` (větev `main`).
- Vercel projekt je napojený na tenhle GitHub repozitář. Každý push do `main` se nasadí automaticky.
- Po každé změně: `git add -A`, `git commit -m "..."`, `git push`. Bez pushe se změna na web nedostane.
- Před commitem/pushem se zeptej Tomáše. Ve Vercelu kliká a nastavuje Tomáš sám, pokud nedovolí jinak.
- Pushuje se přes Git Credential Manager (přihlášení v okně udělá Tomáš). `gh` ani `vercel` CLI tu nejsou.

## Tomáš

Není programátor. Česky, tykat, stručně, kroky „kam kliknout, co napsat“.
