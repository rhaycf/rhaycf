
## Hi!! I'm Rhay

```csharp

public class Perfil
{
  public string Nome { get; private set; }
  public string Graduacao { get; set; }
  public string Estudando { get; set; }
  public string Bebida { get; private set; }
  
  public Perfil(string nome, string graduacao, string estudando, string bebida)
  {
    Nome = nome;
    Graduacao = graduacao;
    Estudando = estudando;
    Bebida = bebida;
  }

  public override string ToString()
  {
    return "Nome: "
        + Nome
        + ",\nGraduação: "
        + Graduacao
        + ",\nEstudando: "
        + Estudando
        + ",\nBebida: "
        + Bebida;
  }
}

//Program.cs
class Program
{
  static void Main(string[] args)
  {
    Perfil perfil = new Perfil(nome: "Rhayane", graduacao: "Sistemas de informação", estudando: ".NET & C#", bebida: "Café ☕");
    
    Console.WriteLine("=== Perfil ===");
    Console.WriteLine(perfil);
  }
}
```
![image](https://github.com/rhaycf/rhaycf/assets/65169776/174b92e1-b528-4288-9425-4c784055e0aa)

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fabres-rhayane/)
