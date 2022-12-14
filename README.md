### P2P platform

```mermaid
    erDiagram
    USERS ||--o{ ADS :  contains
    USERS ||--o{ DELIVERY :  contains
    ADS ||--|{ CATEGORY : contains
    COMPLAINTS ||--|{ USERS : contains
    COMPLAINTS ||--|{ ADS : contains
    ORDER ||--|{ DELIVERY : contains
    ORDER ||--|{ ADS : contains
    ORDER ||--|{ USERS : contains
    CHAT ||--|{ USERS :  contains
    USERS }|--|| CHAT :  contains
```

```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```
```mermaid
    erDiagram
    PRODUCT }|--|| CATEGORY:  contains
    PRODUCT }|--|| PHOTOS:  contains
    PRODUCT ||--|| USERS: contains

    COMMENTS ||--|| PRODUCT: contains
    COMMENTS ||--|| USERS: contains
    COMMENTS ||--O| PHOTOS: contains
    
    CHAT ||--|| USERS: contains
    CHAT ||--|| USERS: contains
    CHAT ||--O| PRODUCT: contains
    
    ORDER }|--|{ PRODUCT: contains
    ORDER }|--|| USERS: contains
    ORDER ||--O| PAYMENT: contains
```

