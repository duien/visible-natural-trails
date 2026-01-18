# Packaging

To create the uploadable zip:

    zip -r visiblenaturaltrails_(jq -r .version modinfo.json).zip . -x '.git/*' -x *.md
