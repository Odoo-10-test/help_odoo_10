Permite hacer herencia y modificar un campo
```
     <record model="ir.ui.view" id="view_company_inherit_form">
        <field name="name">res.company.form.inherit</field>
        <field name="inherit_id" ref="base.view_company_form"/>
        <field name="model">res.company</field>
        <field name="arch" type="xml">
        	<field name="vat" position="replace">
               <field name="vat" placeholder="CL76000000" string="RUT"/>
          </field>
        </field>
    </record>
```