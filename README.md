# CalculaSalarioLiquido

## Acesso ao Git do componente de EditText para moeda
https://github.com/BlacKCaT27/CurrencyEditText

## Configuração do gradle do projeto
```
repositories{
    maven { url "https://jitpack.io" }
}
```
## Configuração do gradle do app
```
dependencies {
    implementation 'com.github.BlacKCaT27:CurrencyEditText:2.0.2'
}
```
## Trecho de código do activity_main.xml
```
    <com.blackcat.currencyedittext.CurrencyEditText
        android:id="@+id/editTextSalario"
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:layout_marginHorizontal="20dp"
        android:layout_marginTop="10dp"/>
```