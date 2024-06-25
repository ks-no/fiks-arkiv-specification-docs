# Conexus - Engage

## Klassifikasjon

### Klassifikasjon 1

_TODO: beskrivelse av denne og en beskrivende navngivning_

```
<klassifikasjon>
    <klassifikasjonssystemID>Conexus - Stafettloggen</klassifikasjonssystemID>
    <klasseID>4.16</klasseID>
    <tittel>Engage</tittel>
</klassifikasjon>
```

### Klassifikasjon 2

_TODO: beskrivelse av denne og en beskrivende navngivning_

```
<klassifikasjon>
    <klassifikasjonssystemID>Conexus - Loggtype</klassifikasjonssystemID>
    <klasseID>4</klasseID>
    <tittel>Kartlegginger</tittel>
</klassifikasjon>
```

### Klassifikasjon 3

_TODO: beskrivelse av denne og en beskrivende navngivning_

```
<klassifikasjon>
    <klassifikasjonssystemID>Conexus - Institusjon</klassifikasjonssystemID>
    <klasseID>**orgnr**</klasseID>
    <tittel>Dummy test school</tittel>
</klassifikasjon>
```

### Klassifikasjon 4

_TODO: beskrivelse av denne og en beskrivende navngivning_

```
<klassifikasjon>
    <klassifikasjonssystemID>Conexus - Person</klassifikasjonssystemID>
    <klasseID>**fnr**</klasseID>
    <tittel>Ola Nordmann</tittel>
</klassifikasjon>
```


### Eksempel arkivmelding

Eksempel er ikke fullstendig, men viser klassifikasjon som eksempel.
Resten av arkivmelding er kuttet vekk. 

```
<?xml version="1.0" encoding="utf-8"?>
<arkivmelding xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema"
              xmlns="https://ks-no.github.io/standarder/fiks-protokoll/fiks-arkiv/arkivmelding/opprett/v1">
    <system>Conexus</system>
    <antallFiler>1</antallFiler>
	<mappe xsi:type="saksmappe">
		<tittel>Test fra Conexus - ny mappe med Carlsten</tittel>
		<klassifikasjon>
			<klassifikasjonssystemID>Conexus - Stafettloggen</klassifikasjonssystemID>
			<klasseID>4.16</klasseID>
			<tittel>Engage</tittel>
		</klassifikasjon>
		<klassifikasjon>
			<klassifikasjonssystemID>Conexus - Loggtype</klassifikasjonssystemID>
			<klasseID>4</klasseID>
			<tittel>Kartlegginger</tittel>
		</klassifikasjon>
		<klassifikasjon>
			<klassifikasjonssystemID>Conexus - Institusjon</klassifikasjonssystemID>
			<klasseID>**orgnr**</klasseID>
			<tittel>Dummy test school</tittel>
		</klassifikasjon>
		<klassifikasjon>
			<klassifikasjonssystemID>Conexus - Person</klassifikasjonssystemID>
			<klasseID>**fnr**</klasseID>
			<tittel>Ola Nordmann</tittel>
		</klassifikasjon>
		...
</arkivmelding>
```