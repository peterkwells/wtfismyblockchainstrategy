[![Build Status](http://img.shields.io/travis/pikesley/wtfismyblockchainstrategy.svg?style=flat-square)](https://travis-ci.org/pikesley/wtfismyblockchainstrategy)
[![Dependency Status](http://img.shields.io/gemnasium/pikesley/wtfismyblockchainstrategy.svg?style=flat-square)](https://gemnasium.com/pikesley/wtfismyblockchainstrategy)
[![Coverage Status](http://img.shields.io/coveralls/pikesley/wtfismyblockchainstrategy.svg?style=flat-square)](https://coveralls.io/r/pikesley/wtfismyblockchainstrategy)
[![Code Climate](http://img.shields.io/codeclimate/github/pikesley/wtfismyblockchainstrategy.svg?style=flat-square)](https://codeclimate.com/github/pikesley/wtfismyblockchainstrategy)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://pikesley.mit-license.org)

# WTFISMYBLOCKCHAINSTRATEGY

It picks a random template from [here](data/templates.yml), and then populates it (randomly) (and recursively) from the [other data](data)

It serves up JSON, of course:

    curl -X GET -H 'Accept: application/json' https://wtfismyblockchainstrategy.herokuapp.com/

I could use some more data though, please send PRs

I think I will probably make this into a _WTFismygenericthing_ generator
