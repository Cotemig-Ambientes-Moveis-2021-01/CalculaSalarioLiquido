# CalculaSalarioLiquido

Git
https://github.com/BlacKCaT27/CurrencyEditText

Configuração do gradle do projeto
<br/>
repositories{<br/>
    maven { url "https://jitpack.io" }<br/>
}<br/>
<br/><br/>
Configuração do gradle do app<br/>
        
dependencies {<br/>
    implementation 'com.github.BlacKCaT27:CurrencyEditText:2.0.2'<br/>
}<br/>
<br/>
    <com.blackcat.currencyedittext.CurrencyEditText
        android:id="@+id/editTextSalario"
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginHorizontal="20dp"
        android:layout_marginTop="10dp"/>
