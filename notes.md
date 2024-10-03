Marek Mikudik 4.C 2.Skupina
Vytvorenie noveho projektu v next.js :

What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*

material ui 

ls – ukazanie suborov
cd – prejdenie do suboru

app – ruter, riesi zakladne komponenty 

page.tsx – root webu 
layout.tsx
not-found.tsx

zaklad stranky:
import Typography from "@mui/material/Typography";

export default function TermsConditions() {
return (
<Typography>podmienky pouzivania tohto webu</Typography>
);
}

vytvorenie .git na githube:
git branch -m main
git config --global user.name "MarekMikudik"
git config --global user.email "marekmikudik@s.zochova.sk"
git remote add origin <link z konta githubu>
git remote -v