# Design Patterns — Complete Visual Reference

A comprehensive visual map of all **152** design patterns implemented in this repository, organized by category.

> For pattern source code, browse each module directory. For the website, visit [java-design-patterns.com](https://java-design-patterns.com/patterns/).

---

## Pattern Landscape

```mermaid
mindmap
  root((Design Patterns 152 total))
    Creational
      18 patterns
      Object creation
    Structural
      26 patterns
      Object composition
    Behavioral
      43 patterns
      Object interaction
    Concurrency
      22 patterns
      Multi-threading
    Architectural
      25 patterns
      System structure
    Functional
      6 patterns
      Functional style
    Idiom
      10 patterns
      Language idioms
    Integration
      2 patterns
      System integration
```

---

## Creational Patterns
*18 patterns — focused on object creation mechanisms, aiming to create objects suited to the situation.*

```mermaid
flowchart LR
    C([🏗️ Creational\n18 patterns])

    C --> AF[Abstract Factory]
    C --> B[Builder]
    C --> CO[Context Object]
    C --> CV[Converter]
    C --> DI[Dependency Injection]
    C --> F[Factory]
    C --> FK[Factory Kit]
    C --> FM[Factory Method]
    C --> MN[Monostate]
    C --> MT[Multiton]
    C --> OM[Object Mother]
    C --> OP[Object Pool]
    C --> P[Property]
    C --> PT[Prototype]
    C --> R[Registry]
    C --> S[Singleton]
    C --> SB[Step Builder]
    C --> VO[Value Object]

    style C fill:#4CAF50,color:#fff,stroke:#388E3C
```

---

## Structural Patterns
*26 patterns — focused on how classes and objects are composed to form larger structures.*

```mermaid
flowchart LR
    S([🔩 Structural\n26 patterns])

    S --> AD[Abstract Document]
    S --> AP[Adapter]
    S --> AM[Ambassador]
    S --> BR[Bridge]
    S --> BD[Business Delegate]
    S --> CO[Composite]
    S --> CE[Composite Entity]
    S --> CV[Composite View]
    S --> DE[Decorator]
    S --> DL[Delegation]
    S --> EV[Embedded Value]
    S --> EA[Event Aggregator]
    S --> FA[Facade]
    S --> FL[Flux]
    S --> FW[Flyweight]
    S --> FC[Front Controller]
    S --> MK[Marker]
    S --> MD[Module]
    S --> PC[Page Controller]
    S --> PO[Page Object]
    S --> PR[Proxy]
    S --> RO[Role Object]
    S --> SI[Separated Interface]
    S --> ST[Strangler]
    S --> TM[Table Module]
    S --> TW[Twin]

    style S fill:#2196F3,color:#fff,stroke:#1565C0
```

---

## Behavioral Patterns
*43 patterns — focused on communication and responsibility between objects.*

```mermaid
flowchart LR
    B([🔄 Behavioral\n43 patterns])

    B --> AV[Acyclic Visitor]
    B --> BC[Bytecode]
    B --> CA[Caching]
    B --> CR[Chain of Responsibility]
    B --> CB[Circuit Breaker]
    B --> CM[Command]
    B --> DL[Data Locality]
    B --> DF[Dirty Flag]
    B --> DB[Double Buffer]
    B --> EO[Extension Objects]
    B --> FT[Feature Toggle]
    B --> GL[Game Loop]
    B --> IM[Identity Map]
    B --> IF[Intercepting Filter]
    B --> IN[Interpreter]
    B --> IT[Iterator]
    B --> LE[Leader Election]
    B --> ME[Mediator]
    B --> MM[Memento]
    B --> NO[Null Object]
    B --> OB[Observer]
    B --> PA[Parameter Object]
    B --> PR[Partial Response]
    B --> PI[Pipeline]
    B --> PP[Poison Pill]
    B --> PM[Presentation Model]
    B --> PQ[Priority Queue]
    B --> RT[Retry]
    B --> SV[Servant]
    B --> SH[Sharding]
    B --> SP[Spatial Partition]
    B --> SC[Special Case]
    B --> SF[Specification]
    B --> ST[State]
    B --> SG[Strategy]
    B --> SS[Subclass Sandbox]
    B --> TM[Template Method]
    B --> TH[Throttling]
    B --> TR[Trampoline]
    B --> TS[Transaction Script]
    B --> TO[Type Object]
    B --> UM[Update Method]
    B --> VI[Visitor]

    style B fill:#FF9800,color:#fff,stroke:#E65100
```

---

## Concurrency Patterns
*22 patterns — focused on multi-threaded and parallel programming.*

```mermaid
flowchart LR
    C([⚡ Concurrency\n22 patterns])

    C --> AO[Active Object]
    C --> AM[Async Method Invocation]
    C --> BK[Balking]
    C --> CO[Commander]
    C --> EA[Event Asynchronous]
    C --> EQ[Event Queue]
    C --> GS[Guarded Suspension]
    C --> HA[Half-Sync Half-Async]
    C --> LF[Leader Followers]
    C --> LO[Lockable Object]
    C --> MW[Master Worker]
    C --> MO[Monitor]
    C --> OL[Optimistic Offline Lock]
    C --> PC[Producer Consumer]
    C --> PR[Promise]
    C --> QL[Queue-Based Load Leveling]
    C --> RE[Reactor]
    C --> RW[Reader-Writer Lock]
    C --> SA[Saga]
    C --> TL[Thread-Local Storage]
    C --> TP[Thread Pool]
    C --> VN[Version Number]

    style C fill:#9C27B0,color:#fff,stroke:#6A1B9A
```

---

## Architectural Patterns
*25 patterns — focused on the overall structure and organization of a system.*

```mermaid
flowchart LR
    A([🏛️ Architectural\n25 patterns])

    A --> AG[Aggregator Microservices]
    A --> AP[API Gateway]
    A --> CS[Client Session]
    A --> CQ[CQRS]
    A --> DA[DAO]
    A --> DB[Data Bus]
    A --> DM[Data Mapper]
    A --> DTO[Data Transfer Object]
    A --> DO[Domain Model]
    A --> ED[Event-Driven Architecture]
    A --> ES[Event Sourcing]
    A --> HX[Hexagonal]
    A --> LA[Layers]
    A --> MM[Metadata Mapping]
    A --> MVC[Model-View-Controller]
    A --> MVI[Model-View-Intent]
    A --> MVP[Model-View-Presenter]
    A --> MVVM[Model-View-ViewModel]
    A --> NO[Naked Objects]
    A --> RP[Repository]
    A --> SE[Serialized Entity]
    A --> SL[Service Layer]
    A --> SC[Service Locator]
    A --> SW[Service-to-Worker]
    A --> UW[Unit of Work]

    style A fill:#F44336,color:#fff,stroke:#B71C1C
```

---

## Functional Patterns
*6 patterns — focused on functional programming principles in an OO context.*

```mermaid
flowchart LR
    F([λ Functional\n6 patterns])

    F --> CP[Collection Pipeline]
    F --> CB[Combinator]
    F --> CU[Currying]
    F --> FI[Filterer]
    F --> FL[Fluent Interface]
    F --> MO[Monad]

    style F fill:#009688,color:#fff,stroke:#00695C
```

---

## Idiom Patterns
*10 patterns — language-specific patterns and coding conventions for Java.*

```mermaid
flowchart LR
    I([☕ Idiom\n10 patterns])

    I --> AA[Arrange Act Assert]
    I --> CB[Callback]
    I --> CL[Collecting Parameter]
    I --> DC[Double-Checked Locking]
    I --> DD[Double Dispatch]
    I --> EA[Execute Around]
    I --> LL[Lazy Loading]
    I --> MI[Mute Idiom]
    I --> PD[Private Class Data]
    I --> RA[Resource Acquisition Is Initialization]

    style I fill:#795548,color:#fff,stroke:#3E2723
```

---

## Integration Patterns
*2 patterns — focused on integrating systems and services.*

```mermaid
flowchart LR
    N([🔗 Integration\n2 patterns])

    N --> FF[Fanout Fan-in]
    N --> TR[Tolerant Reader]

    style N fill:#607D8B,color:#fff,stroke:#263238
```

---

## Pattern Count by Category

```mermaid
xychart-beta
    title "Design Patterns by Category"
    x-axis ["Creational", "Structural", "Behavioral", "Concurrency", "Architectural", "Functional", "Idiom", "Integration"]
    y-axis "Number of Patterns" 0 --> 50
    bar [18, 26, 43, 22, 25, 6, 10, 2]
```

---

## GoF Patterns at a Glance

The original 23 Gang of Four patterns, mapped across the three classic GoF categories:

```mermaid
flowchart TD
    GoF([Gang of Four\n23 Classic Patterns])

    GoF --> CR[Creational]
    GoF --> ST[Structural]
    GoF --> BH[Behavioral]

    CR --> AF[Abstract Factory]
    CR --> BU[Builder]
    CR --> FM[Factory Method]
    CR --> PT[Prototype]
    CR --> SG[Singleton]

    ST --> AD[Adapter]
    ST --> BR[Bridge]
    ST --> CO[Composite]
    ST --> DE[Decorator]
    ST --> FA[Facade]
    ST --> FW[Flyweight]
    ST --> PR[Proxy]

    BH --> CR2[Chain of Responsibility]
    BH --> CM[Command]
    BH --> IT[Iterator]
    BH --> ME[Mediator]
    BH --> MM[Memento]
    BH --> OB[Observer]
    BH --> SA[State]
    BH --> SV[Strategy]
    BH --> TM[Template Method]
    BH --> VI[Visitor]
    BH --> IN[Interpreter]

    style GoF fill:#212121,color:#fff,stroke:#000
    style CR fill:#4CAF50,color:#fff,stroke:#388E3C
    style ST fill:#2196F3,color:#fff,stroke:#1565C0
    style BH fill:#FF9800,color:#fff,stroke:#E65100
```
