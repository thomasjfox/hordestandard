# hordestandard
PHP_CodeSniffer ruleset for Horde

The idea is to create a ruleset that allows code changes
and external contributions to be checked automatically for CS issues.

Example command line invocation:
time phpcs --runtime-set installed_paths /path/to/HordeStandard/parent/dir --standard=HordeStandard -s -p --extensions=php --colors .

The ruleset is in the early alpha stages. Some "considered useful"
rules will be enabled later on. The horde code might need some tweaks
first and some checks (="sniffs") need to be disabled for bundled libraries, too.
