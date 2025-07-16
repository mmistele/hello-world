#!/usr/bin/env python3
s = '#!/usr/bin/env python3\ns = %r\nprint(s %% s)\n"""\n# hello-world\nTesting something\nYeah\nWoohoo\n"""'
print(s % s)
"""
# hello-world
Testing something
Yeah
Woohoo
"""
