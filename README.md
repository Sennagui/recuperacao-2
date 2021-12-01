package sample.model;

public class Produto {

   private String nome;
   private String preco;

   public String getNome() {
       return nome;
   }

   public void setNome(String nome) {
       this.nome = nome;
   }

   public String getPreco() {
       return preco;
   }

   public void setPreco(String preco) {
       this.preco = preco;
   }

   @Override
   public String toString() {
       return "Nome: " + nome + "Preço: " + preco;
   }
}


import sample.model.Produto;

public class Main {


   public static void main(String[] args) {

       Produto produto = new Produto();
       produto.setNome("sabonete");
       produto.setPreco("1,00I");
       System.out.println(produto);

   }

}
