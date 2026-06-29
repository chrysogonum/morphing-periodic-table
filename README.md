# The Morphing Periodic Table

An interactive periodic table that **morphs between five different scientific arrangements** of
the elements, so the relationships between them become visible. The same 118 element tiles physically
fly to their new positions when you switch arrangements.

**Live page:** https://chrysogonum.github.io/morphing-periodic-table/

## The five arrangements
- **Standard** — the familiar 18-column table (lanthanides & actinides detached below).
- **Long form** — the 32-column table with the f-block restored to its true place between groups 2 and 3.
- **Left-step (Janet, 1928)** — ordered by orbital filling; helium sits above beryllium.
- **Spiral** — one continuous Archimedean ribbon from hydrogen outward; atomic number never breaks.
- **Orbits** — each period drawn as a concentric ring, echoing electron shells.

## Features
- Recolor by family, state, electronegativity, ionization energy, atomic mass, density, or melting point.
- Hover any element to light up its whole **group** and **period**.
- Click for a full profile, electron configuration, and a Bohr shell diagram.
- Deep links: `?layout=spiral&color=en&sel=Fe`.

## Data
Element data from the open [Periodic-Table-JSON](https://github.com/Bowserinator/Periodic-Table-JSON)
dataset (CC-BY-SA). Left-step, spiral, and orbit coordinates are computed from each element's block,
period, and group.
