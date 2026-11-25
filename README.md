# Evidence Drceného Polystyrenu

Webová aplikace pro evidenci skladových zásob a prodeje drceného polystyrenu v objemech 0,5 m³ (pytlích).

## 🚀 Živá aplikace (GitHub Pages)
👉 **[https://bildooo.github.io/polystyren-app/](https://bildooo.github.io/polystyren-app/)**

## 👥 Uživatelé a přihlašovací údaje

| Jméno | Heslo | Role | Oprávnění |
| :--- | :--- | :--- | :--- |
| **Robert** | `1111` | Prodejce | Potvrzování dodávek na sklad, odepisování prodeje, evidence tržeb |
| **Martin** | `1234` | Prodejce | Potvrzování dodávek na sklad, odepisování prodeje, evidence tržeb |
| **TomášP** | `1478` | Prodejce | Potvrzování dodávek na sklad, odepisování prodeje, evidence tržeb |
| **Tomáš** | `9876` | Skladník | Přidávání dovezených pytlů na sklady prodejců |
| **Petr** | `1973` | Administrátor | Globální přehled všech skladů, tržeb, dodávek a prodejů |

## 💰 Pravidla a fungování
1. **Skladník (Tomáš)** zadá počet dovezených pytlů pro zvoleného prodejce (Robert, Martin, TomášP).
2. **Prodejce** vidí novou dodávku a musí ji v sekci Přehled **potvrdit** (nebo zamítnout). Teprve po potvrzení se pytle započítají do jeho fyzického skladu.
3. **Prodej**: Prodejce může pytle ze svého skladu prodat. Za každý prodaný pytel přibude do kasy **600 Kč**, zadává se datum a počet kusů.
4. **Administrátor (Petr)** vidí souhrnné statistiky, tržby a stav skladu u všech prodejců.
