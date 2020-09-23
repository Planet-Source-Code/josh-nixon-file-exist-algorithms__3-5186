<div align="center">

## \[\\File Exist Algorithms/\]


</div>

### Description

This function will check to see if a file exist in the computer if it doesnt it will return -1 else 0.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Josh Nixon](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/josh-nixon.md)
**Level**          |Beginner
**User Rating**    |3.4 (81 globes from 24 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Algorithms](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithms__3-29.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/josh-nixon-file-exist-algorithms__3-5186/archive/master.zip)

### API Declarations

```
#include <fstream.h>
```


### Source Code

```
int Check_File(char *FileName)
{
 ifstream FileL;
  FileL.open(FileName);
  if(!FileL)
  {
   FileL.close();
   return -1;
  }
  else
  {
   FileL.close();
   return 0;
  }
}
```

