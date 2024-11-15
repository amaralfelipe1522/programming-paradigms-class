# Paradigmas de Desenvolvimento de Software

## Estrutura do Projeto

```bash
.
├── referencial/
│   ├── concorrente/
│   │   └── docker-compose.yaml
│   ├── declarativo/
│   │   └── docker-compose.yaml
│   ├── funcional/
│   │   └── docker-compose.yaml
│   ├── imperativo/
│   │   └── docker-compose.yaml
│   ├── logico/
│   │   └── docker-compose.yaml
│   ├── orientado-objeto/
│   │   └── docker-compose.yaml
│   ├── reativa/
│   │   └── docker-compose.yaml
└── README.md
```

## Como subir os ambientes

1. Navegue até a pasta referencial:

```bash
cd referencial
```

2. Acesse a pasta de algum paradigma. Por exemplo, _funcional_:

```bash
cd funcional
```

3. Execute o comando para subir os containers:

```bash
docker-compose up -d
```

4. Quando terminar de consultar o material, você pode parar e remover os containers com:

```bash
docker-compose down
```