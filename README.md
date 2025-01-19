graph TB
    subgraph "Système de Gestion des Poubelles Intelligentes"
    Driver((Chauffeur))
    
    Driver --> Login[Se connecter]
    Driver --> Logout[Se déconnecter]
    Driver --> ViewBins[Consulter les poubelles]
    Driver --> FilterBins[Filtrer les poubelles]
    Driver --> ViewMap[Consulter la carte]
    
    ViewBins --> CheckFillLevel[Vérifier niveau de remplissage]
    ViewBins --> CheckLocation[Vérifier localisation]
    FilterBins --> FilterByRegion[Filtrer par région]
    FilterBins --> FilterById[Filtrer par ID]
    ViewMap --> ViewMarkers[Voir marqueurs sur carte]
    ViewMap --> ViewPopups[Voir détails poubelle]
    end
