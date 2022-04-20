# Migrate from classical Jupyter notebook

The following table will help you find the equivalent extensions when migrating
from [the classical notebook](https://jupyter-contrib-nbextensions.readthedocs.io/)
to [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/).

> Feel free to edit this page to add more information by clicking on **Edit on GitHub** in the
> top right corner of this page.

| Classical notebook | JupyterLab | Version |
| --- | --- | --- |
| [(some) LaTeX environments for Jupyter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/latex_envs/README.html) |  |  |
| [2to3 Converter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_prettify/README_2to3.html) |  |  |
| [AddBefore](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/addbefore/readme.html) | Built-in feature (press <kbd>A</kbd> in command mode) | 1+ |
| [Autopep8](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_prettify/README_autopep8.html) | [jupyterlab_code_formatter](https://ryantam626.github.io/jupyterlab_code_formatter/index.html) extension | 2, 3 |
| [AutoSaveTime](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/autosavetime/README.html) | Built-in feature (Settings → Autosave Documents; Advanced Settings → Document Manager) | 1+ |
| [Autoscroll](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/autoscroll/README.html) |  |  |
| [Cell Filter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/cell_filter/README.html) | Built-in Table of Contents heading cells can be filtered by cell tags | 2.2+ |
| [cite2c](https://github.com/takluyver/cite2c) | [jupyterlab-citation-manager](https://github.com/krassowski/jupyterlab-citation-manager) extension | 3+ |
| [Code Font Size](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_font_size/README.html) | Built-in feature (View -> Presentation Mode or Settings -> JupyterLab Theme) | 1+ |
| [Code prettify](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_prettify/README_code_prettify.html) | [jupyterlab_code_formatter](https://ryantam626.github.io/jupyterlab_code_formatter/index.html) extension | 1+ |
| [Codefolding](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/codefolding/readme.html) | Built-in feature (Advanced Settings -> Notebook -> codeCellConfig.codeFolding) | 1+ |
| [Codefolding in Editor](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/codefolding/readme.html) | Built-in feature (Advanced Settings -> Text Editor -> editorConfig.codeFolding) | 1+ |
| [Collapsible Headings](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/collapsible_headings/readme.html) | Built in feature since 3.1 ([PR](https://github.com/jupyterlab/jupyterlab/pull/10260)), for older versions use [aquirdturtle_collapsible_headings](https://github.com/aquirdTurtle/Collapsible_Headings) extension | 1+ |
| [Comment/Uncomment Hotkey](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/comment-uncomment/readme.html) |  |  |
| [datestamper](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/datestamper/readme.html) |  |  |
| [Equation Auto Numbering](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/equation-numbering/readme.html) |  |  |
| [ExecuteTime](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/execute_time/readme.html) | [jupyterlab-execute-time](https://github.com/deshaw/jupyterlab-execute-time) extension | 2+ |
| [Execution Dependencies](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/execution_dependencies/README.html) | Work-in-progress: [ipyspaghetti](https://github.com/cphyc/ipyspaghetti), [akernel](https://github.com/davidbrochart/akernel), [nbsafety](https://github.com/nbsafety-project/nbsafety/issues/87) |  |
| [Exercise](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/exercise/readme.html) |  |  |
| [Exercise2](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/exercise2/readme.html) |  |  |
| [Export Embedded HTML](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/export_embedded/readme.html) |  |  |
| [Freeze](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/freeze/readme.html) |  |  |
| [Gist-it](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/gist_it/readme.html) |  |  |
| [Help panel](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/help_panel/readme.html) | Built-in feature (Help entries open in panels) | 1+ |
| [Hide Header](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hide_header/README.html) | Built-in feature (View -> Simple interface) | 1+ |
| [Hide input](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hide_input/readme.html) | Built-in feature (View -> Collapse Selected Code) | 1+ |
| [Hide input all](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hide_input_all/readme.html) | Built-in feature (View -> Collapse All Code) | 1+ |
| [Highlight selected word](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/highlight_selected_word/README.html) | Built-in feature (Edit -> Find...) | 2+ |
| [highlighter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/highlighter/readme.html) |  |  |
| [Hinterland](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/hinterland/README.html) | [jupyterlab-lsp](https://github.com/krassowski/jupyterlab-lsp) extension | 2+ |
| [Initialization cells](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/init_cell/README.html) | [jupyterlab-autorun-cells](https://github.com/epi2me-labs/jupyterlab-autorun-cells) extension | 2 |
| [isort formatter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/code_prettify/README_isort.html) | [jupyterlab_code_formatter](https://ryantam626.github.io/jupyterlab_code_formatter/index.html) extension | 1+ |
| [Keyboard shortcut editor](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/keyboard_shortcut_editor/README.html) | Built-in feature (Advanced Settings -> Keyboard Shortcuts) | 1+ |
|  | [jupyterlab-shortcutui](https://github.com/jupyterlab/jupyterlab-shortcutui) extension | 2+ |
| [Launch QTConsole](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/qtconsole/README.html) |  |  |
| [Limit Output](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/limit_output/readme.html) |  |  |
| [Move selected cells](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/move_selected_cells/README.html) | Built-in feature (Edit -> Move Cells Up/Down) | 1+ |
| [Navigation-Hotkeys](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/navigation-hotkeys/readme.html) | Built-in feature (Advanced Settings -> Keyboard Shortcuts) | 1+ |
| [nbgrader](https://github.com/jupyter/nbgrader) | | |
| [nbTranslate](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/nbTranslate/README.html) |  |  |
| [Notify](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/notify/readme.html) |[jupyterlab-notifications](https://github.com/mwakaba2/jupyterlab-notifications)|  |
| [Printview](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/printview/readme.html) |  |  |
| [Python Markdown](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/python-markdown/readme.html) |  |  |
| [Rise](https://github.com/damianavila/RISE) |  |  |
| [Rubberband](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/rubberband/readme.html) | Built-in feature (Shift + Left click) | 1+ |
| [Ruler](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/scratchpad/README.html) | Built-in feature (Advanced Settings -> Notebook -> codeCellConfig.rulers) | 1+ |
| [Runtools](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/runtools/readme.html) | Almost all built-in features | 1+ |
| [Scratchpad](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/scratchpad/README.html) | Built-in feature ([connecting code console to notebook](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html)) | 1+ |
| [ScrollDown](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/scroll_down/readme.html) |  |  |
| [Select CodeMirror Keymap](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/select_keymap/README.html) | Built-in feature for File Editor, [jupyterlab-vim](https://github.com/jupyterlab-contrib/jupyterlab-vim) for vim mode in Notebook |  |
| [SKILL Syntax](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/skill/README.html) |  |  |
| [Skip-Traceback](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/skip-traceback/readme.html) |  |  |
| [Snippets](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/snippets/README.html) | [Elyra Code Snippets](https://elyra.readthedocs.io/en/latest/user_guide/code-snippets.html) extension | 2+ |
| [Snippets Menu](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/snippets_menu/readme.html) | [jupyterlab-code-snippets](https://github.com/jupytercalpoly/jupyterlab-code-snippets) extension | 2+ |
|  | [jupyterlab-snippets](https://github.com/QuantStack/jupyterlab-snippets) extension | 2+ |
| [spellchecker](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/spellchecker/README.html) | [jupyterlab-spellchecker](https://github.com/jupyterlab-contrib/spellchecker) extension | 1+ |
| [Split Cells Notebook](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/splitcell/readme.html) |  |  |
| [Table of Contents (2)](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/toc2/README.html) | Built-in feature | 3+ |
|  | [@jupyterlab/toc](https://github.com/jupyterlab/jupyterlab-toc) extension | 1, 2 |
| [table_beautifier](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/table_beautifier/README.html) |  |  |
| [Toggle all line numbers](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/toggle_all_line_numbers/readme.html) | Built-in feature (View -> Show Line Numbers) | 1+ |
| [Tree Filter](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/tree-filter/readme.html) | Built-in feature | 3+ |
| [Variable Inspector](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/varInspector/README.html) | [lckr-jupyterlab-variableinspector](https://github.com/lckr/jupyterlab-variableInspector) extension | 1+ |
| [zenmode](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/zenmode/README.html) | Built-in feature | 1+ |

If you don't find what you are looking here or in the web, you can always start coding a new extension; for
more information have a look at the [documentation](https://jupyterlab.readthedocs.io/en/stable/extension/extension_dev.html).
