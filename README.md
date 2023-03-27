# Yolo_filer
Filer til bruk av Yolo-trening

## .CFG
Under mappen "CFG" finn du ulike cfg filer for å trene opp ulike versjonar av Yolo
Last ned/kopier ønska cfg fil, og gjer endringar i fila i henhold til prosedyren

## .DATA og .NAMES
Under mappen "DATA og NAMES" finn du .DATA fil og .NAMES fil.
Last ned/kopier desse to, og gjer endringar i henhold til prosedyre.

### .NAMES
.NAMES filen innholder kun navn på dei ulike klassene du skal trene algoritmen på

### DATA
.DATA filen skal vere ferdig tilpassa til bruk med tilhøyrande Google Colab Notebook.
Du kan gjere endringar i .DATA filen om det er ønskelig, men du må då også huske å gjere endringar i COlab Notebooken.

.DATA filen:
    -Linje 1: Antall klasser du skal trene på. Må samsvare med antall navn i .NAMES filen.
    -Linje 2: Filstien til ei tekstfil som angjev bilete, samt tilhøyrande annotering til trenings-datasettet ditt.
    -Linje 3: Filstien til ei tekstfil som angjev bilete, samt tilhøyrande annotering til validerings-datasettet ditt.
    -Linje 4: filstien til .NAMES filen.  
    -Linje 5: inneholder informasjon om kor du vil lagre midlertidig og endelige weights.
