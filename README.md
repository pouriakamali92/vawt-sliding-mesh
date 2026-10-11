# Aerodynamische Simulation einer vertikalen Windturbine (VAWT)

Strömungssimulation eines VAWT-Rotors mit schräg geneigten Blättern im Vergleich zu einem Rotor mit geraden, vertikalen Blättern, geplant mit der Sliding-Mesh-Methode in Ansys Fluent.

**Art:** eigenständiges Projekt
**Status:** 🚧 in Bearbeitung (Vernetzungsphase). Es liegen weder eine abgeschlossene Simulation noch quantitative Ergebnisse vor.
**Software:** Ansys SpaceClaim, Ansys Fluent

## Idee

Die drei Rotorblätter sind, anders als bei der üblichen Bauform mit vertikal-parallelen Blättern, schräg nach außen geneigt und über geschwungene, sattelförmige Arme an die zentrale Nabenwelle angebunden. Verglichen werden soll diese Anordnung mit einem konventionellen Rotor mit geraden vertikalen Blättern, anhand von Leistungsbeiwert, Drehmoment und Strömungsphänomenen wie Strömungs- und Wirbelablösung.

## Geplante Methodik

- Stationäre Außendomäne, über ein Interface mit einem rotierenden Bereich um den Rotor gekoppelt
- Sliding Mesh: Das Netz des rotierenden Bereichs bewegt sich in jedem Zeitschritt relativ zum stationären Bereich. Die Simulation wird deshalb transient aufgesetzt.

## Stand

Die Geometrie steht. Die Vernetzung von rotierendem und stationärem Bereich ist in Arbeit. Simulation und Ergebnisse folgen und werden hier ergänzt.

Portfolio: <https://pouria-kamali.de/projekt-vawt.php>
