<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

- Shopping items live in the `rancho_items` table (RLS per user) and are read/written from the browser client with a realtime subscription; why: per-account sync across devices.
- `/` is the public sign-in page; signed-in pages live under `src/routes/_authenticated/`; why: single client-side auth gate.
