# Aastaaruande kontrollija

Vibecodingu töötoa projekt — veebiäpp, mis kontrollib mikroettevõtja aastaaruande vastavust nõuetele.

## Kuidas alustada

### 1. Klooni projekt

Ava Cursor, ava terminal (Terminal → New Terminal) ja kirjuta:

git clone https://github.com/SINU-KASUTAJANIMI/aastaaruande-kontroll.git
cd aastaaruande-kontroll

### 2. Installi sõltuvused

npm install

### 3. Seadista keskkonnamuutujad

Kopeeri näidisfail:

cp .env.example .env

Ava .env fail ja asenda väärtused (saad juhendajalt):

VITE_SUPABASE_URL=siia-tuleb-supabase-url
VITE_SUPABASE_ANON_KEY=siia-tuleb-supabase-key
VITE_OPENAI_API_KEY=siia-tuleb-openai-key

### 4. Käivita äpp

npm run dev

Ava brauseris: http://localhost:5173

## Kasulikud Cursori käsud

- **Ctrl+L** (Mac: Cmd+L) — ava AI chat
- **Ctrl+K** (Mac: Cmd+K) — muuda koodi AI-ga
- **@PRD.md** — viita PRD failile AI chatist
- **@failinimi** — viita suvalisele failile
