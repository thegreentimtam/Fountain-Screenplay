# Fountain Screenplay
This template is for writing screenplays with Fountain, and includes an action to automatically generate PDFs when you push to the main branch.

## Using this template

Click the **Use this Template** button, and create a repository for your screenplay. Write your screenplay using [fountain](https://fountain.io/) syntax in the `screenplay.fountain` file. When you push changes to the main branch, the PDF will automatically be updated with your script. 

The PDF export settings are kept in the `config.json` file. See [here](https://github.com/ifrost/afterwriting-labs/blob/master/docs/clients.md#config-file) for the available options. Some options you may wish to edit include:
- Changing `print_profile` from `"a4"` to `"usletter"` if you are in the United States
- Changing `scene_numbers` to `"both"` when you want to include scene numbers in your script.

## Better Fountain

I recommend editing your script using Better Fountain for Visual Studio Code. This will give you many features, including previews, syntax highlighting, automatic scene numbering, and screenplay statistics. 