# Suricata and Evebox combo for easy deploy with docker compose
As part of the build: suricata -- IPS/IDS itself, eve box -- a web interface for it. 
Port for accessing the web interface: 5636

# TODO
- [ ] Replace the rules with English-language ones. (Still in Portuguese)


-------------------

# Средство обнаружения вторжений Suricata и легковестный веб-интерфейс EveBox

В составе сборки: suricata -- сама IPS/IDS, evebox -- веб-морда для неё. 
Порт для доступа к веб-интерфейсу: 5636
```
suricta-main/          # Корневая директория
│
├── rules/             # Директория с правилами для обнаружения. Примонтирована к контейнеру Suricata.
│   └── <rules_files>
│
├── logs/              # Директория с логами
│   └──  <logs_files>
│
├── docker-compose.yml # Файл конфигурации для запуска всего кластера
└── suricata.yaml      # Файл конфигурации IPS/IDS Suricata
```
# TODO
- [ ] Заменить правила на свежие англоязычные. (Пока на португальском)
