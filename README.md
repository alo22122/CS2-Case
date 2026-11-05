# CS2 Vault — Collection Platform

A static, beginner-friendly CS2 collection website prototype.

## Included
- Responsive dashboard and sidebar navigation
- Collection catalogue with category filters and search
- Sample skin database with rarity filters
- Local demo inventory and favourites
- Challenges, points, XP and sample leaderboard
- Editable demo profile
- Admin dashboard preview
- Browser localStorage persistence

## Run it on GitHub Pages
1. Open your GitHub repository.
2. Upload `index.html`, `styles.css`, and `app.js` to the repository root.
3. Commit the files to the `main` branch.
4. In **Settings → Pages**, select **Deploy from a branch**, `main`, and `/(root)`.
5. Open your published GitHub Pages URL.

No build command or local installation is required.

## Important demo limitations
This version is frontend-only. User data is stored in the visitor's browser using localStorage. It does not yet provide real accounts, shared inventories, secure admin access, or a hosted database. The admin page is only a preview and must not be treated as secure.

The sample points are fictional, have no cash value, and cannot be bought, sold, transferred or withdrawn. The project intentionally uses non-wagering challenges rather than betting games.

## Next production step
Create a Supabase project and configure authentication, database tables, row-level security, and server-side admin roles. Do not put a Supabase service-role key in frontend code.
