FROM odoo:17.0

USER odoo

COPY ./compose/local/odoo/etc/odoo.conf /etc/odoo/odoo.conf
COPY ./compose/local/odoo/etc/requirements.txt /etc/odoo/requirements.txt

RUN pip install -r /etc/odoo/requirements.txt
