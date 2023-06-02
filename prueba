let mapa = new Map();

mapa.set("clave", "valor");

console.log(mapa.get("clave"));

mapa.set("clave1", "valor1");
mapa.set("clave2", "valor2");

mapa.forEach((valor, clave) => {
  console.log(`Clave: ${clave}, Valor: ${valor}`);
});

let arr = [1, 2, 3, 1, 2, 3, 4, 5, 6, 4, 5, 6, 7, 8, 9, 7, 7,8, 9];
let duplicados = contarDuplicados(arr);

for (let [num, count] of duplicados) {
    console.log(`Número: ${num}, Cantidad: ${count}`);
}

function contarDuplicados(arr) {
let mapa = new Map();

 for (let i = 0; i < arr.length; i++) {
if (mapa.has(arr[i])) {
            mapa.set(arr[i], mapa.get(arr[i]) + 1);
        }
else {
            mapa.set(arr[i], 1);
        }
    }

let duplicados = new Map();

 for (let [num, count] of mapa) {
if (count > 1) {
            duplicados.set(num, count);
        }
    }
return duplicados;
}
