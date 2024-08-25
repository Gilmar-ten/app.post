// Component de um item do cardápio
function ItemCardapio({ nome, descricao, preco, imagem }) {
  return (
    <div className="item">
      <img src={imagem} alt={nome} />
      <h3>{nome}</h3>
      <p>{descricao}</p>
      <span>R$ {preco}</span>
      <button>Adicionar ao carrinho</button>
    </div>
  );
}