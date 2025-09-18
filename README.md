# Seminář Algoritmizace a programování 2025-26
#### Vedoucí semináře: Josefína Paloudová (email: [josefina.paloudova@lauder.cz](mailto:josefina.paloudova@lauder.cz))

<details>
  <summary><h4>Anotace</h4></summary>
V tomto semináři se seznámíme se základními koncepty teoretické informatiky v podobě, v jaké se studuje na VŠ. Výchozím textem při průchodu seminářem budou tzv. korespondenční semináře informatiky poskytované dvěma prominentními fakultami, které informatiku jako bakalářský studijní obor nabízí: **Matematicko-fyzikální fakulta Univerzity Karlovy** a **Fakulta informatiky Masarykovy univerzity**. EDIT: Na setkání 11/09/2025 jsem byla upozorněna, že tyto semináře nejsou jediné dva existující semináře tohoto typu u nás. Doplňuji tedy, že je možné v rámci předmětu plnit i semináře pod záštitou **Fakulty informačních technologií Českého vysokého učení technického** a **Katedry informatiky Přírodovědecké fakulty Univerzity Jana Palackého**.
Moje role jakožto vedoucí semináře bude převážně **mentorská**: budu vám k dispozici s radou v případě nejasností a postrčením v případě poklesu motivace. Naše pravidelná setkání budou probíhat ve znamení samostatné práce a individuálních konzultaci šitých na míru vašich potřeb.  V případě, že se bude zdát, že by celá skupina nebo její část profitovala ze společné lekce na určité téma, po domluvě s vámi ji zařadím.
</details>

#### Něco o korespondenčních seminářích
Jedná se vlastně o každoroční seriál úloh z informatiky zveřejňovaných po dobu školního roku, doplněných o vzdělávací texty. Autory všech materiálů jsou převážně současní a bývalí studenti daných fakult a katedry. Zatřešující témata seminářů se mění napříč ročníky, ale základ zůstává pevně ukotvený v klíčových konceptech algoritmizace a teoretické informatiky. Všechny semináře obsahují úlohy, které jsou individuálně vyhodnocovány skutečnými lidmi a bodovány. Pro účast v hodnocení je potřeba vypracování úloh odevzdat v předem daném termínu.

Významným aspektem korespondenčních seminářů je také pravidlo, že jejich úspěšné vyřešení vám může zajistit odpuštění přijímací zkoušky do bakalářských programů na odpovídající fakultě/katedře. Dále bývá zvykem, že je možnost se vedle online vyplňování úloh účastnit také různých osobních setkání. Více najdete v souboru [Korespondenční semináře](korespondencni_seminare.md).


### Aktuality
👉17/09/2025 **V KSP a ve FIKS, tedy obou pražských seminářích, byly spuštěny první vlny úloh. Datum odevzdání pro oba semináře je 19.10.2025**

## 2. setkání 18/09/2025
### Možnosti práce
<details>
  <summary><b>1. Pokud chcete pomoct s nastavením integrovaného programovacího prostředí (IDE) na vlastním notebooku:</b></summary>
  <ol type="a">
      <li><details> <summary> Pro úplné začátečníky doporučuji IDLE, což je prostředí, které je rovnou nainstalované spolu s Pythonem.</summary>
       <ol>
         <li>Poté, co si stáhnete Python a nainstalujete podle níže uvedených instrukcí, otevřete si program "IDLE (Python 3.x)".</li>
        <li>Otevře se vám shellové okno tohoto prostředí (tady se budou zobrazovat výstupy spuštěných skriptů). Nyní otevřete menu Soubor/File a vyberte možnost Nový/New file.</li>
        <li>V nově otevřeném editovacím okně můžete psát kód.</li>
         </ol>
        </details>
    </li>
      <li> Pokud už máte nějakou zkušenost s jiným IDE, můžete klidně používat to, pokud podporuje i Python.</li>
      <li> Pokud vaše preferované IDE nepodporuje Python, doporučuju <a href="https://code.visualstudio.com/docs/setup/setup-overview">nainstalovat Visual Studio Code</a> a připojit <a href="https://code.visualstudio.com/docs/python/python-tutorial">interpret Pythonu</a>, nebo používat IDLE, vizte bod a.</li>
  --> <a href="https://docs.python.org/3/using/windows.html">Zde</a> jsou instrukce k instalaci Pythonu na počítač s operačním systémem Windows 10 a vyšším.
      <li> Poslední možností je používat jakékoli online prostředí, což s sebou ale nese další věci na zvážení, vizte bod 2.</li>
</details>
<details>
   <summary><b>2. Pokud chcete pokračovat v kurzu Základů programování v Pythonu bez vlastního notebooku:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>
<details>
   <summary><b>3. Pokud víte/tušíte, že budete chtít podávat přihlášku na jakýkoli bakalářský program na matfyzu, a chcete si vysoutěžit odpuštění přijímací zkoušky:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>
<details>
   <summary><b>4. Pokud víte/tušíte, že budete chtít podávat přihlášku na FIT, a chcete si vysoutěžit odpuštění přijímací zkoušky:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>
<details>
   <summary><b>5. Pokud víte/tušíte, že budete chtít podávat přihlášku na FI MUNI nebo KI UPOL, a nechce se vám registrovat v žádném jiném ze seminářů:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>
<details>
   <summary><b>6. Pokud víte/tušíte, že chcete jít studovat informatiku, ale ještě nevíte kam:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>
<details>
   <summary><b>7. Pokud byste radši než na některém ze seminářů pracovali na vlastním projektu:</b></summary><br>
<i>Na doplnění se pracuje.</i>
</details>



## 1. setkání 11/09/2025
### Možnosti práce
- práce v semináři bude s ohledem na nepříliš vysoký počet účastníků probíhat na **třech úrovních**, z nichž každá dostane jiné množství pozornosti z mojí strany
- vzhledem k tomu, že v naší skupině je poměrně rozmanitá škála různých úrovní zkušenosti, **nechávám na vás, abyste vyhodnotili, který přístup bude pro vás nejvhodnější** – svoje rozhodnutí navíc můžete kdykoli v průběhu školního roku změnit a flexibilně se připojit k jiné úrovni
1. **Pokud si nejste jisti úplnými základy programování**: V první fázi semináře spolu projdeme základy programování v Pythonu. Oporou nám k tomu bude zatím základní kurz programování v Pythonu na stránkách [https://ksp.mff.cuni.cz/](https://ksp.mff.cuni.cz/kurz/#task/placeholder-kurz-programovani). EDIT: ~~Během prvního setkání si nachystáme prostředí pro další práci.~~ Tohle se nestalo, omlouvám se, vrátíme se k tomu 18/09/2025.
2. **Pokud základy umíte, ale chcete rozšířit svoji znalost běžných algoritmů a pocvičit se**: Vzhledem k tomu, že ani jeden z korespondenčních seminářů, které mají tvořit páteř tohoto semináře, ještě nejsou v tomto ročníku rozjeté, doporučuju vaší pozornosti kurz Teoretická informatika prakticky na [stránkách KSP](https://ksp.mff.cuni.cz/kurz/#).
3. **Pokud základy umíte a chcete pracovat na vlastním projektu**: Na dnešním setkání prosím pracujte na sestavení detailního plánu práce na zbytek školního roku.

