# ✈ FlightCheck

**A clean, offline-capable cockpit checklist app for pilots — built as a single HTML file, installable on any Android tablet.**

![FlightCheck Banner](https://img.shields.io/badge/Aircraft-B737%20%7C%20A320-1a6fe8?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMS4xMyAxNC4wNmwtMS40MS0xLjQxLTkuMTkgOS4xOS0yLjgzLTIuODMgOS4xOS05LjE5LTEuNDEtMS40MS05LjE5IDkuMTktMi44Mi0yLjgzIDkuMTktOS4xOS0xLjQxLTEuNDEtOS4xOSA5LjE5TDAgMTJsNC4yNCA0LjI0IDIuODMtMi44MyAyLjgzIDIuODMtMi44MyAyLjgzTDEyIDI0bDE0LjE0LTE0LjE0eiIvPjwvc3ZnPg==)
![Platform](https://img.shields.io/badge/Platform-Android%20Tablet-green?style=for-the-badge)
![Offline](https://img.shields.io/badge/Works-Offline-orange?style=for-the-badge)

---

## 📱 Screenshots

<table>
<tr>
<td align="center" width="33%">

**Home Screen**

<svg xmlns="http://www.w3.org/2000/svg" width="220" height="360" viewBox="0 0 220 360">
  <!-- Phone frame -->
  <rect width="220" height="360" rx="20" fill="#e8e8e8"/>
  <rect x="6" y="6" width="208" height="348" rx="16" fill="#ffffff"/>
  <!-- Status bar -->
  <rect x="6" y="6" width="208" height="24" rx="16" fill="#f4f4f4"/>
  <!-- Content area -->
  <rect x="6" y="30" width="208" height="324" rx="0" fill="#ffffff"/>
  <!-- Plane icon -->
  <text x="110" y="110" font-size="44" text-anchor="middle" font-family="serif">✈</text>
  <!-- Title -->
  <text x="110" y="145" font-size="16" font-weight="bold" text-anchor="middle" fill="#1a1a1a" font-family="sans-serif">FLIGHTCHECK</text>
  <text x="110" y="162" font-size="10" text-anchor="middle" fill="#999999" font-family="sans-serif">Cockpit Checklist System</text>
  <!-- Theme toggle -->
  <rect x="75" y="172" width="70" height="22" rx="11" fill="none" stroke="#c8c8c8" stroke-width="1.5"/>
  <text x="110" y="187" font-size="9" text-anchor="middle" fill="#555555" font-family="sans-serif">🌙 Dark mode</text>
  <!-- B737 button -->
  <rect x="22" y="204" width="176" height="58" rx="10" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <rect x="22" y="204" width="5" height="58" rx="2" fill="#1a6fe8"/>
  <text x="44" y="228" font-size="22" font-family="serif">🛫</text>
  <text x="76" y="228" font-size="15" font-weight="bold" fill="#1a6fe8" font-family="sans-serif">B737</text>
  <text x="76" y="243" font-size="8" fill="#999999" font-family="sans-serif">BOEING 737 · NORMAL PROCEDURES</text>
  <!-- A320 button -->
  <rect x="22" y="272" width="176" height="58" rx="10" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <rect x="22" y="272" width="5" height="58" rx="2" fill="#d95f2b"/>
  <text x="44" y="296" font-size="22" font-family="serif">🛩</text>
  <text x="76" y="296" font-size="15" font-weight="bold" fill="#d95f2b" font-family="sans-serif">A320</text>
  <text x="76" y="311" font-size="8" fill="#999999" font-family="sans-serif">AIRBUS A320 · NORMAL PROCEDURES</text>
</svg>

</td>
<td align="center" width="33%">

**Checklist Menu**

<svg xmlns="http://www.w3.org/2000/svg" width="220" height="360" viewBox="0 0 220 360">
  <rect width="220" height="360" rx="20" fill="#e8e8e8"/>
  <rect x="6" y="6" width="208" height="348" rx="16" fill="#f4f4f4"/>
  <!-- Top bar -->
  <rect x="6" y="6" width="208" height="42" rx="16" fill="#ffffff"/>
  <rect x="6" y="30" width="208" height="18" fill="#ffffff"/>
  <rect x="6" y="30" width="208" height="1" fill="#e0e0e0"/>
  <text x="20" y="26" font-size="9" fill="#1a1a1a" font-family="sans-serif">◀ HOME</text>
  <text x="80" y="26" font-size="12" font-weight="bold" fill="#1a6fe8" font-family="sans-serif">B737</text>
  <text x="168" y="26" font-size="9" fill="#cc3333" font-family="sans-serif">⟳ RESET</text>
  <!-- Menu items -->
  <!-- Completed items (green) -->
  <rect x="12" y="50" width="196" height="38" rx="8" fill="#eaf6ee" stroke="#a8d9b8" stroke-width="1.5"/>
  <text x="24" y="66" font-size="8" fill="#999" font-family="sans-serif">01</text>
  <text x="40" y="66" font-size="11" font-weight="600" fill="#2e9e5b" font-family="sans-serif">PREFLIGHT</text>
  <text x="168" y="66" font-size="9" fill="#2e9e5b" font-family="sans-serif">10/10</text>
  <text x="188" y="67" font-size="13">✅</text>
  <rect x="12" y="96" width="196" height="3" rx="1" fill="#a8d9b8" opacity="0.3"/>
  <!-- Completed -->
  <rect x="12" y="96" width="196" height="38" rx="8" fill="#eaf6ee" stroke="#a8d9b8" stroke-width="1.5"/>
  <text x="24" y="112" font-size="8" fill="#999" font-family="sans-serif">02</text>
  <text x="40" y="112" font-size="11" font-weight="600" fill="#2e9e5b" font-family="sans-serif">BEFORE START</text>
  <text x="162" y="112" font-size="9" fill="#2e9e5b" font-family="sans-serif">12/12</text>
  <text x="188" y="113" font-size="13">✅</text>
  <!-- In progress -->
  <rect x="12" y="142" width="196" height="38" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <text x="24" y="158" font-size="8" fill="#999" font-family="sans-serif">03</text>
  <text x="40" y="158" font-size="11" font-weight="600" fill="#1a1a1a" font-family="sans-serif">AFTER START</text>
  <text x="168" y="158" font-size="9" fill="#999" font-family="sans-serif">3/5</text>
  <text x="188" y="159" font-size="11" fill="#999">▶</text>
  <rect x="12" y="177" width="118" height="3" rx="1" fill="#2e9e5b"/>
  <!-- Remaining -->
  <rect x="12" y="188" width="196" height="38" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <text x="24" y="204" font-size="8" fill="#999" font-family="sans-serif">04</text>
  <text x="40" y="204" font-size="11" font-weight="600" fill="#1a1a1a" font-family="sans-serif">TAXI</text>
  <text x="174" y="204" font-size="9" fill="#999" font-family="sans-serif">0/5</text>
  <text x="188" y="205" font-size="11" fill="#999">▶</text>
  <rect x="12" y="234" width="196" height="38" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <text x="24" y="250" font-size="8" fill="#999" font-family="sans-serif">05</text>
  <text x="40" y="250" font-size="11" font-weight="600" fill="#1a1a1a" font-family="sans-serif">BEFORE TAKEOFF</text>
  <text x="168" y="250" font-size="9" fill="#999" font-family="sans-serif">0/7</text>
  <text x="188" y="251" font-size="11" fill="#999">▶</text>
  <rect x="12" y="280" width="196" height="38" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <text x="24" y="296" font-size="8" fill="#999" font-family="sans-serif">06</text>
  <text x="40" y="296" font-size="11" font-weight="600" fill="#1a1a1a" font-family="sans-serif">AFTER TAKEOFF</text>
  <text x="168" y="296" font-size="9" fill="#999" font-family="sans-serif">0/6</text>
  <text x="188" y="297" font-size="11" fill="#999">▶</text>
</svg>

</td>
<td align="center" width="33%">

**Checklist Items**

<svg xmlns="http://www.w3.org/2000/svg" width="220" height="360" viewBox="0 0 220 360">
  <rect width="220" height="360" rx="20" fill="#e8e8e8"/>
  <rect x="6" y="6" width="208" height="348" rx="16" fill="#f4f4f4"/>
  <!-- Top bar -->
  <rect x="6" y="6" width="208" height="52" rx="16" fill="#ffffff"/>
  <rect x="6" y="42" width="208" height="16" fill="#ffffff"/>
  <rect x="6" y="58" width="208" height="1" fill="#e0e0e0"/>
  <text x="20" y="26" font-size="9" fill="#1a1a1a" font-family="sans-serif">◀ BACK</text>
  <text x="78" y="26" font-size="11" font-weight="bold" fill="#1a1a1a" font-family="sans-serif">BEFORE START</text>
  <text x="20" y="42" font-size="8" fill="#999" font-family="sans-serif">B737 · 3 / 12 COMPLETE</text>
  <!-- Checked items -->
  <rect x="12" y="66" width="196" height="36" rx="8" fill="#eaf6ee" stroke="#a8d9b8" stroke-width="1.5"/>
  <rect x="20" y="74" width="20" height="20" rx="4" fill="#2e9e5b"/>
  <text x="30" y="88" font-size="11" text-anchor="middle" fill="white" font-family="sans-serif">✓</text>
  <text x="50" y="82" font-size="10" font-weight="600" fill="#555" font-family="sans-serif">FUEL QUANTITY</text>
  <text x="50" y="94" font-size="8" fill="#999" font-family="sans-serif">CHECKED ____</text>
  <rect x="12" y="108" width="196" height="36" rx="8" fill="#eaf6ee" stroke="#a8d9b8" stroke-width="1.5"/>
  <rect x="20" y="116" width="20" height="20" rx="4" fill="#2e9e5b"/>
  <text x="30" y="130" font-size="11" text-anchor="middle" fill="white" font-family="sans-serif">✓</text>
  <text x="50" y="124" font-size="10" font-weight="600" fill="#555" font-family="sans-serif">PASSENGER SIGNS</text>
  <text x="50" y="136" font-size="8" fill="#999" font-family="sans-serif">ON</text>
  <rect x="12" y="150" width="196" height="36" rx="8" fill="#eaf6ee" stroke="#a8d9b8" stroke-width="1.5"/>
  <rect x="20" y="158" width="20" height="20" rx="4" fill="#2e9e5b"/>
  <text x="30" y="172" font-size="11" text-anchor="middle" fill="white" font-family="sans-serif">✓</text>
  <text x="50" y="166" font-size="10" font-weight="600" fill="#555" font-family="sans-serif">WINDOWS</text>
  <text x="50" y="178" font-size="8" fill="#999" font-family="sans-serif">CLOSED &amp; LOCKED</text>
  <!-- Unchecked items -->
  <rect x="12" y="192" width="196" height="36" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <rect x="20" y="200" width="20" height="20" rx="4" fill="none" stroke="#c8c8c8" stroke-width="2"/>
  <text x="50" y="208" font-size="10" font-weight="600" fill="#1a1a1a" font-family="sans-serif">FLIGHT DECK DOOR</text>
  <text x="50" y="220" font-size="8" fill="#555" font-family="sans-serif">CLOSED &amp; LOCKED</text>
  <rect x="12" y="234" width="196" height="36" rx="8" fill="#ffffff" stroke="#e0e0e0" stroke-width="1.5"/>
  <rect x="20" y="242" width="20" height="20" rx="4" fill="none" stroke="#c8c8c8" stroke-width="2"/>
  <text x="50" y="250" font-size="10" font-weight="600" fill="#1a1a1a" font-family="sans-serif">TRANSPONDER</text>
  <text x="50" y="262" font-size="8" fill="#555" font-family="sans-serif">TA/RA</text>
  <!-- Progress footer -->
  <rect x="6" y="330" width="208" height="24" rx="0" fill="#ffffff"/>
  <rect x="6" y="329" width="208" height="1" fill="#e0e0e0"/>
  <rect x="6" y="329" width="50" height="3" rx="1" fill="#2e9e5b"/>
  <text x="20" y="344" font-size="8" fill="#999" font-family="sans-serif">3 / 12 ITEMS</text>
  <text x="158" y="344" font-size="8" fill="#999" font-family="sans-serif">IN PROGRESS</text>
</svg>

</td>
</tr>
<tr>
<td align="center" colspan="3">

**Dark Mode**

<svg xmlns="http://www.w3.org/2000/svg" width="460" height="200" viewBox="0 0 460 200">
  <rect width="460" height="200" rx="16" fill="#111111"/>
  <!-- Left: home dark -->
  <rect x="10" y="10" width="200" height="180" rx="12" fill="#1e1e1e"/>
  <text x="110" y="55" font-size="32" text-anchor="middle">✈</text>
  <text x="110" y="82" font-size="13" font-weight="bold" text-anchor="middle" fill="#f0f0f0" font-family="sans-serif">FLIGHTCHECK</text>
  <text x="110" y="97" font-size="8" text-anchor="middle" fill="#666" font-family="sans-serif">Cockpit Checklist System</text>
  <rect x="70" y="104" width="80" height="18" rx="9" fill="none" stroke="#444" stroke-width="1.5"/>
  <text x="110" y="117" font-size="8" text-anchor="middle" fill="#aaa" font-family="sans-serif">☀️ Light mode</text>
  <rect x="18" y="130" width="184" height="24" rx="8" fill="#1e1e1e" stroke="#333" stroke-width="1.5"/>
  <rect x="18" y="130" width="5" height="24" rx="2" fill="#4a90e8"/>
  <text x="35" y="147" font-size="10" font-weight="bold" fill="#4a90e8" font-family="sans-serif">B737</text>
  <rect x="18" y="160" width="184" height="24" rx="8" fill="#1e1e1e" stroke="#333" stroke-width="1.5"/>
  <rect x="18" y="160" width="5" height="24" rx="2" fill="#e8763a"/>
  <text x="35" y="177" font-size="10" font-weight="bold" fill="#e8763a" font-family="sans-serif">A320</text>
  <!-- Right: checklist dark -->
  <rect x="250" y="10" width="200" height="180" rx="12" fill="#1e1e1e"/>
  <rect x="250" y="10" width="200" height="36" rx="12" fill="#1e1e1e"/>
  <rect x="250" y="46" width="200" height="1" fill="#333"/>
  <text x="265" y="30" font-size="8" fill="#f0f0f0" font-family="sans-serif">◀ BACK</text>
  <text x="323" y="30" font-size="10" font-weight="bold" fill="#f0f0f0" font-family="sans-serif">PREFLIGHT</text>
  <text x="265" y="43" font-size="7" fill="#666" font-family="sans-serif">B737 · 2 / 10 COMPLETE</text>
  <rect x="258" y="54" width="184" height="30" rx="7" fill="#1a2e22" stroke="#2a5c3a" stroke-width="1.5"/>
  <rect x="265" y="61" width="16" height="16" rx="3" fill="#3dba6e"/>
  <text x="273" y="73" font-size="9" text-anchor="middle" fill="white" font-family="sans-serif">✓</text>
  <text x="290" y="69" font-size="9" font-weight="600" fill="#aaa" font-family="sans-serif">OXYGEN</text>
  <text x="290" y="79" font-size="7" fill="#666" font-family="sans-serif">100%, NORMAL</text>
  <rect x="258" y="90" width="184" height="30" rx="7" fill="#1a2e22" stroke="#2a5c3a" stroke-width="1.5"/>
  <rect x="265" y="97" width="16" height="16" rx="3" fill="#3dba6e"/>
  <text x="273" y="109" font-size="9" text-anchor="middle" fill="white" font-family="sans-serif">✓</text>
  <text x="290" y="105" font-size="9" font-weight="600" fill="#aaa" font-family="sans-serif">NAV TRANSFER SW</text>
  <text x="290" y="115" font-size="7" fill="#666" font-family="sans-serif">NORMAL</text>
  <rect x="258" y="126" width="184" height="30" rx="7" fill="#1e1e1e" stroke="#333" stroke-width="1.5"/>
  <rect x="265" y="133" width="16" height="16" rx="3" fill="none" stroke="#444" stroke-width="2"/>
  <text x="290" y="141" font-size="9" font-weight="600" fill="#f0f0f0" font-family="sans-serif">AIR DATA SWITCHES</text>
  <text x="290" y="151" font-size="7" fill="#aaa" font-family="sans-serif">NORMAL</text>
</svg>

</td>
</tr>
</table>

---

## ✨ Features

- **Two aircraft types** — Boeing 737 and Airbus A320 normal procedures
- **10 checklists per aircraft** — from Preflight all the way through Shutdown
- **Visual completion tracking** — checklist items turn green when tapped, no strikethrough
- **Menu progress indicators** — each checklist shows item count and a progress bar; turns fully green when complete
- **Light & dark mode** — toggle on the home screen, preference saved automatically
- **Reset button** — clears all checklists for the current aircraft with one tap
- **Big back button** — at the bottom of each checklist for easy one-hand navigation on a tablet
- **Fully offline** — no internet required after install
- **Saves state** — your progress is remembered if you close and reopen the app

---

## 📲 Installation on Android Tablet

1. Open **Chrome** on your tablet
2. Navigate to the GitHub Pages URL
3. Tap the **3-dot menu → Add to Home Screen**
4. The app installs and opens fullscreen — no browser bar, just like a native app

---

## ✈ Checklists Included

| Phase | B737 | A320 |
|---|---|---|
| Preflight / Cockpit Prep | ✓ | ✓ |
| Before Start | ✓ | ✓ |
| After Start | ✓ | ✓ |
| Taxi | ✓ | ✓ |
| Before Takeoff | ✓ | ✓ |
| After Takeoff / Climb | ✓ | ✓ |
| Descent | ✓ | ✓ |
| Approach | ✓ | ✓ |
| Landing | ✓ | ✓ |
| Shutdown | ✓ | ✓ |

---

## 🛠 Built With

- Pure HTML, CSS, JavaScript — no frameworks, no dependencies
- Single self-contained `.html` file
- Web App Manifest for PWA installation
- `localStorage` for state persistence

---

> *For simulator and study use. Always refer to official airline procedures for real operations.*
