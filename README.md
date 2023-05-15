# Atividade1-4anoInfo
 // Inicialização de dados
let contacts = [{ nome: "João", telefone: "9999-9999" }, { nome: "Maria", telefone: "8888-8888" }];

// Funções CRUD
function createContact(nome, telefone) {
contacts.push({ nome: nome, telefone: telefone });
}

function readContact(index) {
return contacts[index];
}

function updateContact(index, newNome, newTelefone) {
contacts[index].name = newNome;
contacts[index].phone = newTelefone;
}

function deleteContact(index) {
contacts.splice(index, 1);
}
