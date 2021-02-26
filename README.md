# CalculaSalarioLiquido

<strong>Acesso ao Git do componente de EditText para moeda</strong><br/>
https://github.com/BlacKCaT27/CurrencyEditText

<strong>Configuração do gradle do projeto</strong><br/>
repositories{<br/>
    maven { url "https://jitpack.io" }<br/>
}<br/>
<br/><br/>
<strong>Configuração do gradle do app</strong><br/>
dependencies {<br/>
    implementation 'com.github.BlacKCaT27:CurrencyEditText:2.0.2'<br/>
}<br/>
<br/><br/>
<strong>Trecho de código do activity_main.xml</strong><br/>
    <com.blackcat.currencyedittext.CurrencyEditText<br/>
        android:id="@+id/editTextSalario"<br/>
        android:layout_width="match_parent"<br/>
        android:layout_height="50dp"<br/>
        android:layout_marginHorizontal="20dp"<br/>
        android:layout_marginTop="10dp"/><br/>
