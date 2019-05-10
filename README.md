# Decoder
難読化されたテキストを平文に戻すスクリプトです。ローカルで使用可能です。(ネットワーク環境が不要です)  
エンコード方式を選択し、エンコード文を左のテキストエリアに貼り付けて、”れっつでこーど”ボタンを押下してください。  
右のテキストエリアにデコード結果が表示されます。多重エンコードされている場合、下のテキストエリアは自動で更新されます。  

■デコード機能  
・base64  
&nbsp;末尾のイコール無しでもデコード可能です。  
・URLエンコード  
  パーセントエンコードとも言います。%が含まれている文字列があった場合は試してみてください。  
・ASCII（10進数）  
  10進数で表記されたASCII文字をデコードできます。区切り文字は、半角スペースかカンマ、もしくはもしくはchr(x)+chr(y)の形式(PHPやpythonで使われる)で表記して使用してください。  
・ASCII（16進数）  
  16進数は"0x"付いてても付いてなくてもデコードできますが、半角スペースなどには対応していません。区切り文字は使用しないでください。  
  （例：6578616d706c65）  
  
 ■多重デコード機能  
 難読化された文字列には、何重にもエンコードされた文字列が存在します。既存のデコードスクリプトでは、多重エンコードされた文字列は全体像が掴みにくいです。  
 Decoder.htmlでは、多重エンコードされた文字列のデコード結果を自動で更新し表示することで、全体像が把握しやすくなっています。  
 
  

# Dependency  
HTMLとJavaScriptを使用しています。JavaScriptの機能を有効にしてから使用してください。  

# Setup  
Decoder.htmlをダウンロードし、ブラウザで開いてください。  

# Licence  
このスクリプトはMIT Licenseのもと公開しています。LICENSE.mdを参照してください。  

# Authors  
RenTonogi  
