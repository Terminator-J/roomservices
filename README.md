# roomservices
XML manifests for actually trying to build ROMs with various device trees/branches. 
Apparently the dirty little not-so-secret is that most build instructions don't actually work. They never bother making sure that everything listed in SomeROM.dependencies actually resolve, and get automagically pulled into roomservice.xml and added when doing a 'repo sync'. 

So without the actual roomservice.xml files (or whatever other manifests one adds; you're now free to add as many as you want and they get parsed in alphabetical order, capture the magic) you're just guessing. Here are some that work, or don't, as noted by branch. 
