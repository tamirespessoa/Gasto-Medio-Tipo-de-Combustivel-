# Gasto-Medio-Tipo-de-Combustivel-

const Gasolina = 4.79;
const Etanol = 3.79;
const kmPorLitros = 10;
const distanciaEmKM = 100;
const tipoCombustivel = 'Gasolina';

const litrosConsumidos = distanciaEmKM / kmPorLitros;

if (tipoCombustivel === 'Etanol') {
    const valorGasto = litrosConsumidos * Etanol;
    console.log(valorGasto.toFixed(2));

} else  {
    const valorGasto = litrosConsumidos * Gasolina;
    console.log(valorGasto.toFixed(2));
}




