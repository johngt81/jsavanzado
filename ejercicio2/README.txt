Crear un micro test framework.

Vamos a seguir el formato:
describe(name, function() {
  it(name, function() {
    assert.assertEquals(...);
    assert.assertNotEquals(...);
  });
});

Implementar los métodos en microtest.js de manera tal que
al ejecutar "node codeTest.js" obtengamos la siguiente respuesta:

$ cd <la_carpeta_del_ejercicio>
$ node codeTest.js 
 Running test:  Code test
   Running test:  Basic tests
     [PASSED] Our lib should be defined
     [PASSED] Should have an add function defined
     [PASSED] Should have a concat funtion defined
   Running test:  Functionality tests
     [PASSED] Should add properly
     [PASSED] Should concat properly
   Running test:  This one fails
     [FAILED] Should fail
   [PASSED] A passing it
