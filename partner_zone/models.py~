# -*- coding: utf-8 -*-

from openerp import models, fields, api, _

class partner_zone(models.Model):
   _inherit = 'res.partner'

    # Add a new column to the res.partner model, by default partners are not
   
   zone = fields.Char(string="Zone", required=False)
   neighborhood = fields.Char(string="Neighborhood", required=False)
   routing = fields.Integer(string="Routing")

    # session_ids = fields.Many2many('openacademy.session',
    #     string="Attended Sessions", readonly=True)
