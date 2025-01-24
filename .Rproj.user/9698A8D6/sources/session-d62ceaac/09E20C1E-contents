# Liste des packages nécessaires
required_packages <- c(
  "dplyr",
  "ggplot2",
  "readxl",
  "zoo",
  "grDevices",
  "tibble",
  "magrittr"
)

# Fonction pour installer les packages manquants
install_if_missing <- function(pkg) {
  if (!requireNamespace(pkg, quietly = TRUE)) {
    install.packages(pkg, dependencies = TRUE)
  }
}

# Installation des packages
lapply(required_packages, install_if_missing)

cat("All the necessary packages have been installed.\n")
