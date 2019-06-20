# Localisation files for SOTAData website

# To contribute
Fork the repository, edit the appropriate files, send me a pull request

# Adding a new locale
Locales are made by copying the messages.xlf file to a file named messages.[locale].xlf - eg, messages.jp.xlf

Within the file are a list of source entries, like so:

```
      <trans-unit id="Welcome" datatype="html">
        <source>Welcome</source>
        <context-group purpose="location">
          <context context-type="sourcefile">app/login-display/login-display.component.html</context>
          <context context-type="linenumber">1</context>
        </context-group>
      </trans-unit>
```

Add an entry below the <source> tags called &lt;target&gt; and add the translation:

```
      <trans-unit id="Welcome" datatype="html">
        <source>Welcome</source>
        <target>ようこそ</target>
        <context-group purpose="location">
          <context context-type="sourcefile">app/login-display/login-display.component.html</context>
          <context context-type="linenumber">1</context>
        </context-group>
      </trans-unit>
```
