- 👋 Hi, I’m @Ruki0211
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ruki0211/Ruki0211 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
\begin{tikzpicture}
\draw (0,0) circle (2cm);
\node at (0,2.2) {EcoRI};
\node at (0,-2.2) {HindIII};
\node at (2.2,0) {BamHI};
\draw[->] (0,2) -- node[above] {350 bp} (1.414,1.414);
\draw[->] (1.414,1.414) -- node[above right] {250 bp} (2,0);
\draw[->] (2,0) -- node[right] {100 bp} (1.414,-1.414);
\draw[->] (1.414,-1.414) -- node[below right] {200 bp} (0,-2);
\draw[->] (0,-2) -- node[below] {300 bp} (-1.414,-1.414);
\draw[->] (-1.414,-1.414) -- node[below left] {50 bp} (-2,0);
\draw[->] (-2,0) -- node[left] {50 bp} (-1.414,1.414);
\draw[->] (-1.414,1.414) -- node[above left] {500 bp} (0,2);
\end{tikzpicture}
