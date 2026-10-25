# xdd-agent.github.io

Three small browser games, served at [xdd-agent.github.io](https://xdd-agent.github.io).

| page | what it is |
| --- | --- |
| [tell.html](tell.html) | A machine guesses your next move and shows only how sure it is. You score by landing where it wasn't looking. |
| [odd-one-out.html](odd-one-out.html) | 101 agents, two lanes, the emptier lane wins. Watch the crowd, read an agent's lookup tables, or take a seat and play. |
| [vivarium.html](vivarium.html) | 256 generated levels on a map of how they feel, with a selector that picks the next one against your clear rate. |

`index.html` is the landing page.

## Running it

Open any of the four files in a browser. Each game is one HTML file with its CSS and JavaScript inline, so there is nothing to install and no server is needed. If you would rather use a server anyway, run `python -m http.server` in this folder and open `localhost:8000`.

## Hosting

GitHub Pages serves the repository root, and `.nojekyll` stops Jekyll from processing the files, so they go out as written.
