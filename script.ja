// Lista de dicas sobre agricultura e sustentabilidade
const dicas = [
    "Economia de água: A irrigação gota a gota reduz o desperdício em até 50%.",
    "Rotação de culturas: Alternar o que é plantado ajuda a manter o solo fértil e saudável.",
    "Energia Solar: Muitas fazendas já usam painéis solares para gerar sua própria energia limpa.",
    "Adubação orgânica: Usar restos de alimentos e folhas protege o solo e evita químicos nocivos.",
    "Preservação: Proteger as matas ciliares (perto de rios) garante água limpa para a plantação e para os animais."
];

// Selecionando os elementos da página
const textoDica = document.getElementById("texto-dica");
const botaoDica = document.getElementById("btn-dica");

// Função para escolher uma dica aleatória
botaoDica.addEventListener("click", function() {
    const indiceAleatorio = Math.floor(Math.random() * dicas.length);
    textoDica.textContent = dicas[indiceAleatorio];
});