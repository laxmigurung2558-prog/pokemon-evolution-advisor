# Pokévolve — Pokémon Evolution Advisor

A static, responsive Pokémon evolution comparison website built for the Pokémon case assignment. Includes 811 Pokémon from the provided dataset, search, evolution branches, sprite images, and base-stat comparisons.

## Run locally

From this folder run `python3 -m http.server 8000` and visit http://localhost:8000.

## Publish on GitHub Pages

1. Create a **public** GitHub repository (for example, `pokemon-evolution-advisor`).
2. Upload `index.html`, `style.css`, `app.js`, and `pokemon.json` to the repository root.
3. Open **Settings → Pages** and choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
4. Wait for GitHub Pages to deploy. Your website URL will normally be `https://YOUR-USERNAME.github.io/pokemon-evolution-advisor/`.
5. Submit both the live website URL and repository URL.

## Limitations and methodology

The recommendation is based on the difference in **total base stats** between a Pokémon and its direct evolution(s). It does **not** assess competitive usefulness, game-specific evolution requirements, moves, abilities, or battle matchups. Evolution links come from `evolves_from_species_id` in the provided CSV. Images use publicly hosted PokéAPI sprites by numeric ID; an unavailable sprite is hidden. The website requires internet access for those sprites and the optional Google Fonts.

## Submission statements (edit to reflect your actual work)

- **Time spent:** [Enter your actual total time, including review, testing, and deployment].
- **Cost:** GitHub Pages hosting: $0 on a public repository. Development: $0 in direct charges if using existing/free tools. AI assistance: ChatGPT was used to generate initial website code; [state your actual subscription/usage cost and any relevant usage-limit consumption].
