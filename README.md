Demo 
https://chrisdel101.github.io/chris-del-portfolio

### Running

The baseurl and url not work properly and so we need two configs. We need to run the dev config manually so that the main config can be set to run as is on github pages and not break.

__Local run__

use `config_dev.yaml` with flag to run the correct baseUrl without the appended params. 

    Run: `bundle exec jekyll serve --config _config.yml,_config_dev.yml`
