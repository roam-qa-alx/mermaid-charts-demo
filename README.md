## Flow chart
```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

## Pokemon flow chart
```mermaid
  graph TD;
      Charmander-->Charmeleon;
      Charmeleon-->Charizard;
```

## User journey
```mermaid
journey
    title Who joins me for activities
    section .
      breaky: 1: son, daughter, tea
      morning walk: 3: son
      working in garage: 7: tea
      late afternoon: 5: son, daughter
      before bed: 4: son
      midnight: 6: tea
```
## Pie chart
```mermaid
pie showData title Junk on my desk 
    "Fruit" : 2
    "Devices" : 6
    "Stationary" : 4
    "Sanitizer": 3
```

## Sequence diagram
```mermaid 
sequenceDiagram title: A day at the cafe
    Barister ->> Alex: Howdy mate, how are you?
    Alex-->>Alex: Oh god, interpersonal communication
    Alex-->>Alex: Don't say something stupid
    Alex ->> Barister: Yes
    Barister ->> Alex: Oh haha ... what can I get you today?
    Alex ->> Barister: 1 cap thanks
    Barister ->> Alex: No dramas, coming up mate
    Alex -x Seat: Imma go sit down
    Seat-->>Seat: Geez, settle down big fella
    Seat-->>Seat: It's been a while since <br/> I've had human connection
    Barister ->> Alex: Here's 1 cap mate
    Alex ->> Barister: Ah cheers! Have a good one
    Barister -> Barister: A good one
    Barister -> Barister: good one
    Barister -> Barister: good ... evil
    Barister -> Barister: to sides of the same coin
    Note right of Barister: Alex leaves, a stranger walks in
    Barister -x Stranger: Howdy! What can I get you today?
    Seat -x Alex: Farewell bipedal friend, it was an honour to hold you on this Earth
    Note right of Seat: Seat waits patiently for the next human connection<br/>
    Stranger --> Stranger: Imma go sit down now
    Seat -x Stranger: Well hello there 🥹
```



## Links
- https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/
- https://mermaid-js.github.io/mermaid/#/README
- https://mermaid-js.github.io/mermaid/#/./integrations
