# TITULO

Teste de markdown

## O que faz:
**negrito**
*itálico*
_linha sublinhada_
_sublinhada **composta com negrito** fica assim_

###### titulo pequeno

## LISTA1
* python
* javascript

### Lista ordenada:
1. Load script
2. Edit script
3. Save script

# PULEI O TUTORIAL PARA INSERÇÃO DE IMAGENS E LINKS

## Inserção de código
``` javascript
function MainScriptLoad()
{
    // Procura o script principal
    var arquivoScript = new File(path_scripts  + mainScriptName + '.' + scriptExtension);

    // Chama o script
    if (arquivoScript.exists)
    {
        //alert (arquivoScript.fullName);

        $.evalFile(arquivoScript);        
    }
    else
    {
        alert(('O SCRIPT PRINCIPAL NÃO FOI ENCONTRADO:\n\n' + arquivoScript.fullName), 'ERRO', true);
    }
}
```

```c#
        private void btnHelpProjeto_Click(object sender, EventArgs e)
        {
            MessageBox.Show("Indique para onde devo copiar as pastas do projeto.", "AJUDA", MessageBoxButtons.OK, MessageBoxIcon.Information);
        }
```
