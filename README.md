# core-adminlte-scaffold

**INSTRUÇÕES** <br>
*Utilize o composer para instalação da dependência:* <br/>
  composer require italomatos/core-adminlte-scaffold <br>
**Vai uma cópia da pasta para seu diretório _resources/_** <br/>
Escolha a opção: <br/>
 *Provider: Coredigital\Scaffold\CoreScaffoldProvider*
> Pronto! Agora você tem tudo em suas mãos. <br/>

Com esse comando de exemplo você cria a sua migrate, o seu Model, seu Controller e sua View. <br/>
php artisan core:scaffold Contact name:string telephone:bigInteger <br/>
<br/>
**ESTRUTURA** <br/>

- *app/Contact.php*, "Com protected $fillable = ['name','telephone'];" <br/>
- *app/Http/Controllers/Admin/ContactController.php* "Com todos os metodos prontos" <br/>
- *database/migrations/create_contacts_table*,"Com os campos name e telephone"<br/><br/>
- *resources/views/contacts/* **:**
 * **index.blade.php** <br/>
 * **create.blade.php** <br/>
 * **edit.blade.php** <br/>
 > Já usando o recurso do plugin **Datatables** com todos os campos escrito no comando
 <br/>
 <br/>
 ## AGORA É SÓ USAR!
