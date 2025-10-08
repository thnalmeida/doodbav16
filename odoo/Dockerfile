ARG ODOO_VERSION
FROM ghcr.io/tecnativa/doodba:${ODOO_VERSION}-onbuild

CMD ["odoo", "-c", "/opt/odoo/auto/odoo.conf", "--init=base"]
