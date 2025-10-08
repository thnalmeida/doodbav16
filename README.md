[![Doodba deployment](https://img.shields.io/badge/deployment-doodba-informational)](https://github.com/Tecnativa/doodba)
[![Last template update](https://img.shields.io/badge/last%20template%20update-v9.0.0-informational)](https://github.com/Tecnativa/doodba-copier-template/tree/v9.0.0)
[![Odoo](https://img.shields.io/badge/odoo-v16.0-a3478a)](https://github.com/odoo/odoo/tree/16.0)
[![OEEL-1.0 license](https://img.shields.io/badge/license-OEEL--1.0-critical})](LICENSE)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://pre-commit.com/)

# odoo - a Doodba deployment

Para conseguir usar a aplicação localmente: 
1) No repositório raiz do projeto: `docker compose up`
2) Em seguida: `docker exec doodba-v16-odoo-1 odoo -d devel --init=base --stop-after-init --without-demo=all`
3) Posteriormente: invoke git-aggregate
4) E, então: ` docker compose restart`

Depois, verifique a porta exposta pelo "proxy" para acessar a aplicação localmente. 
This project is a Doodba scaffolding. Check upstream docs on the matter:

- [General Doodba docs](https://github.com/Tecnativa/doodba).
- [Doodba copier template docs](https://github.com/Tecnativa/doodba-copier-template)
- [Doodba QA docs](https://github.com/Tecnativa/doodba-qa)

# Credits

This project is maintained by:

[![Tecnativa](https://www.tecnativa.com/r/H3p)](https://www.tecnativa.com/r/bb4)

Also, special thanks to
[our dear community contributors](https://github.com/Tecnativa/doodba-copier-template/graphs/contributors).
