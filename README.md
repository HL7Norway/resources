# Felles ressurser

Ressurser til bruk i andre prosjekter/repositories. Skrivebeskyttet (forhåpentligvis) - ta [kontakt](https://github.com/rockphotog) hvis du ønsker å legge noe her.

## Snapshots

Et snapshot (øyeblikksbilde) i sammenheng med FHIR-profiler refererer til en komplett, statisk instans av en profil på et bestemt tidspunkt. Det inkluderer alle elementene og begrensningene definert i profilen, noe som muliggjør konsekvent validering og bruk på tvers av ulike systemer.

### Eksempel

Hente ned og installere hl7.fhir.no.basis-2.2.0

```sh
curl -L -o hl7.fhir.no.basis-2.2.0-snapshots.tgz https://raw.githubusercontent.com/HL7Norway/resources/main/snapshots/hl7.fhir.no.basis-2.2.0-snapshots.tgz
npm install hl7.fhir.no.basis-2.2.0-snapshots.tgz
```

Alternativt

```sh
npm install https://raw.githubusercontent.com/HL7Norway/resources/main/snapshots/hl7.fhir.no.basis-2.2.0-snapshots.tgz
```
