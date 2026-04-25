diff --git a/README.md b/README.md
index 46081b8a13414541321b36b20f990b4b2ea0ad75..e0cf6a61269a85c9c7f157aaee28d0a9a584afbb 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,11 @@
 # footer
 wildhermes
+
+## Kuvien käyttö
+Projektissa on valmiit kuvapaikat, jotta footer näkyy heti ilman puuttuvia tiedostoja:
+- `assets/aurora-panorama.svg`
+- `assets/wildhermes-logo.svg`
+
+Jos haluat käyttää omia kuvia, korvaa nämä tiedostot tai päivitä polut:
+- `styles.css` → `url("assets/aurora-panorama.svg")`
+- `index.html` → `<img src="assets/wildhermes-logo.svg" ...>`
