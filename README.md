# SharpDoc :construction_worker:

Csharp Documentation Generator from XML File

### Important

Actually, i can't upload the code because it's pretty ugly lol.
You can try to download your documentation with this online demo : https://julienravia.fr/doc/

Code example for generating documentation : 
```
<?php
include 'vendor/autoload.php';

$doc = new SharpDoc\XmlReader('XMLFile.xml');
$doc = $doc->genDatas();
$gen = new SharpDoc\DocGenerator('folder', $doc);
$gen->gen('resources.zip'); // ressources to extract (CSS, Javascript files)
```

### Work In Progress
Waiting for a clean code to release :ok_hand:

## Authors
Thanks to 
**[Mehdi BENBAHRI](https://github.com/MehdiBenbahri)**

## License

[MIT](LICENSE.md) @ SharpDoc :construction_worker:


