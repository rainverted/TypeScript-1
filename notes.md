1. Compiler instaliavimas - npm install -g typescript
   - compiler TS koda pavercia i JS koda
   - cd - change directory, norint pereiti i kita dir
2. Pasileisti compiler -
   - viena faila - tsc [reikiama dir] -> pvz. tsc index.ts
   - daug failu/visus - {"include": ["./*"]} -> tsc
3. Sukuriame tsconfig.json (json = javascript object notation):
   - Auto compile - {"compileOnSave": true} arba terminale tsc --watch
4. Patikrinti versija tsc -v

Important TS notes:

- Kintamasis negali buti be reiksmes, bet reiksme gali (tik jos neistrauksime)
- svarbu griežtai apibrezti kintamajo tipa
- kintamojo masyvas -> const vardai : string[]
- kintamojo tipas funkcijoje:
  - visoms reiksmems -> function suma (sk1, sk2) : number {}
  - reiksmei -> function suma (sk1:number, sk2:string) : number {}
  - masyvo naudojimas -> function zmones (vardai: Array<>) : void {}
  - masyvo naudojimas -> function zmones (vardai: string[]) : void {}
- void - funkcija, kuri nieko negrazina????
- iterator = i/array[i]

NOTE:

- grupeje vykdant projekta siunciame tik sukompiliuota JS faila

LINKS:
https://www.typescriptlang.org/
https://www.typescriptlang.org/docs/handbook/2/classes.html
