esse é um dos codigos

o return é usado em Funçoes e é bem Util

Exemplo:
```
class Main {
  static function main() {
    trace(pathFormater("fakeLibrarys", "json"));
  }
  
  static function pathFormater(aa:String, type:String) {
    // esse codigo vai retornar o lugar do path
    return "assets/" + aa + "." +type.toLowerCase();
  }
}
```

Resultado: ``` assets/fakeLibrarys.json ```

é bem util para fazer sistemas de matematicas ou de paths