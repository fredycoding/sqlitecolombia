# Base de datos SQLITE - MUNICIPIOS DE COLOMBIA
Base de datos en SQLITE de los Departamentos y Municipios de Colombia, incluyendo las ciudades.
______________________________________________________________________________________________

# Para llenar un Spinner en Android Studio con los departamentos:

ArrayAdapter <CharSequence> adapter = ArrayAdapter.createFromResource(this,R.array.departamentos,R.layout.support_simple_spinner_dropdown_item);
        adapter.setDropDownViewResource(R.layout.support_simple_spinner_dropdown_item);
        espinerdpto.setAdapter(adapter);

y el listado lo guarda en este ejemplo en RES / VALUES / datos_spinner_dpto.xml
<?xml version="1.0" encoding="utf-8"?>
<resources>

    <string-array name="departamentos">
        <item>ANTIOQUIA</item>
        <item>ATLÁNTICO</item>
        <item>BOGOTÁ, D.C.</item>
        <item>BOLÍVAR</item>
        <item>BOYACÁ</item>
        <item>CALDAS</item>
        <item>CAQUETÁ</item>
        <item>CAUCA</item>
        <item>CESAR</item>
        <item>CÓRDOBA</item>
        <item>CUNDINAMARCA</item>
        <item>CHOCÓ</item>
        <item>HUILA</item>
        <item>LA GUAJIRA</item>
        <item>MAGDALENA</item>
        <item>META</item>
        <item>NARIÑO</item>
        <item>NORTE DE SANTANDER</item>
        <item>QUINDIO</item>
        <item>RISARALDA</item>
        <item>SANTANDER</item>
        <item>SUCRE</item>
        <item>TOLIMA</item>
        <item>VALLE DEL CAUCA</item>
        <item>ARAUCA</item>
        <item>CASANARE</item>
        <item>PUTUMAYO</item>
        <item>SAN ANDRÉS Y PROVIDENCIA</item>
        <item>AMAZONAS</item>
        <item>GUAINÍA</item>
        <item>GUAVIARE</item>
        <item>VAUPÉS</item>
        <item>VICHADA</item>
    </string-array>

</resources>
