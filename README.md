# CalculaSalarioLiquido

## Acesso ao Git do componente de EditText para moeda
https://github.com/BlacKCaT27/CurrencyEditText

## Configuração do gradle do projeto
```
repositories{<br/>
    maven { url "https://jitpack.io" }<br/>
}
```
## Configuração do gradle do app
```
dependencies {
    implementation 'com.github.BlacKCaT27:CurrencyEditText:2.0.2'<br/>
}
```
## Trecho de código do activity_main.xml
```
    <com.blackcat.currencyedittext.CurrencyEditText<br/>
        android:id="@+id/editTextSalario"<br/>
        android:layout_width="match_parent"<br/>
        android:layout_height="50dp"<br/>
        android:layout_marginHorizontal="20dp"<br/>
        android:layout_marginTop="10dp"/><br/>
```