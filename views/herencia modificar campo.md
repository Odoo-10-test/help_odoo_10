Permite hacer herencia y adicionar un campo
```
     <record model="ir.ui.view" id="view_company_inherit_form">
        <field name="name">res.company.form.inherit</field>
        <field name="inherit_id" ref="base.view_company_form"/>
        <field name="model">res.company</field>
        <field name="arch" type="xml">
           <field name="state_id" position="after">
                <field name="city_id" placeholder="Comuna" style="width: 100%" options='{"no_open": True}'/>
          </field>
        </field>
    </record>
```