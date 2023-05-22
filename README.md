# uml

#Diagrama actividad
```mermaid
stateDiagram-v2

parado : Parado
agachado : Agachado
saltando :  Saltando
caminando : Caminando
corriendo : Corriendo

parado -->agachado
parado --> saltando
agachado-->saltando
saltando-->parado
parado-->caminando
parado-->corriendo
caminando -->corriendo
corriendo-->caminando
```

