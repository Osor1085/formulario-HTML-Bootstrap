# formulario-HTML-Bootstrap
<!DOCTYPE html>
    <head>
    	<meta name="viewport" content="width=device-width, initial-scale=1, maximun-scale=1, user-scalable=no">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384  ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>catalogo de ventas</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    </head>
    <body>
            <div class="p-3 mb-2 bg-success text-white" style="text-align:justify"><h1>CATALOGO DE VENTAS TIENDA "EL DEPORTISTA"</h1></div>
        <div class="container">
			<form action="" method="POST">
            <table border="3" align=center>
                <tr>
                    <td colspan="6" style="text-align:center">
                            <div class="p-3 mb-2 bg-primary text-white">INFORMACION DEL VENDEDOR</div>
                    </td>
                </tr>
                <tr>
                    <td style="text-align:center"><h3>Nombre</h3></td>
                    <td>
                        <input type="text" size="37" placeholder="Nombre vendedor" required>
                    </td>
                    <td style="text-align:center"><h3>Apellido</h3></td>
                    <td>
                        <input type="text" size="37"  placeholder="Apellido vendedor" required>
                    </td>
                    <td style="text-align:center"><h3>Cedula</h3></td>
                    <td>
                        <input type="text" size="40" placeholder="Cedula vendedor" required>
                    </td>
                </tr>
                <tr>
                        <td colspan="6" style="text-align:center">
                                <div class="p-3 mb-2 bg-primary text-white">INFORMACION DEL COMPRADOR</div>
                        </td>
                    </tr>
                    <tr>
                        <td style="text-align:center" ><h3>Nombre</h3></td>
                        <td>
                            <input type="text" size="37" placeholder="Nombre comprador" required>
                        </td>
                        <td style="text-align:center"><h3>Apellido</h3></td>
                        <td>
                            <input type="text" size="37" placeholder="Apellido comprador" required>
                        </td>
                        <td style="text-align:center"><h3>Cedula</h3></td>
                        <td>
                            <input type="text" size="40" placeholder="Cedula comprador" required>
                        </td>
                    </tr>
                    <tr>
                        <td style="text-align:center"><h3>Telefono</h3></td>
                        <td>
                            <input type="text" size="37"  placeholder="Telefono comprador" required>
                        </td>
                        <td style="text-align:center"><h3>Direccion</h3></td>
                        <td colspan="4">
                            <input type="text" size="122" placeholder="Direccion comprador" required>
                        </td>
                    </tr>
                    <tr>
                        <td colspan="6" style="text-align:center">
                            <div class="p-3 mb-2 bg-warning text-white"><h2>CATALOGO DE PRODUCTOS</h2></div>
                        </td>
                    </tr>
                    <tr>
                            <td colspan="6" style="text-align:center">
                                 <div class="p-3 mb-2 bg-primary text-white">CAMISAS DEPORTIVAS</div>
                            </td>
                     </tr>
                     
                    <tr>
                        <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa1.jpg">
                                        <div class="card-body">
                                         <div class="p-3 mb-2 bg-primary text-white">Chelsea<br>Precio:75000</div>
                                        <input type="checkbox">
                                        </div>
                                      </div>
                        </td>
                        <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa2.jpg">
                                        <div class="card-body">
                                         <div class="p-3 mb-2 bg-primary text-white">Barcelona<br>Precio:75000</div>   
                                        <input type="checkbox">
                                        </div>
                                      </div>
                         </td>
                         <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa3.jpg">
                                        <div class="card-body">
                                        <div class="p-3 mb-2 bg-primary text-white">Real Madrid<br>Precio:75000</div>
                                        <input type="checkbox">
                                        </div>
                                      </div>
                        </td>
                        <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa4.jpg">
                                        <div class="card-body">
                                                <div class="p-3 mb-2 bg-primary text-white">Juventus<br>Precio:75000</div>
                                        <input type="checkbox">
                                        </div>
                                      </div>
                         </td>
                         <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa5.jpg">
                                        <div class="card-body">
                                                <div class="p-3 mb-2 bg-primary text-white">Manchester United<br>Precio:75000</div>
                                        <input type="checkbox">
                                        </div>
                                      </div>
                         </td>
                         <td style="text-align:center">
                                <div class="card" style="width: 19rem;">
                                        <img src="camisa6.jpg">
                                        <div class="card-body">
                                                <div class="p-3 mb-2 bg-primary text-white">Bayern Munich<br>Precio:75000</div>
                                        <input type="checkbox">
                                        </div>
                                      </div>
                         </td>
                    </tr>
                    <tr>
                         <td colspan="6" style="text-align:center">
                                <div class="p-3 mb-2 bg-primary text-dark">GUAYOS</div></td>
                        </tr>
                    <tr>
                    <tr>
                            <td style="text-align:center">
                                    <div class="card" style="width: 19rem;">
                                            <img src="guayos1.jpg" class="rounded-pill">
                                            <div class="card-body">
                                                    <div class="p-3 mb-2 bg-primary text-dark">Precio:1800000</div>
                                            <input type="checkbox">
                                            </div>
                                        </div>
                            </td>
                            <td style="text-align:center">
                                    <div class="card" style="width: 19rem;">
                                            <img src="guayos2.jpg" class="rounded-pill">
                                            <div class="card-body">
                                                    <div class="p-3 mb-2 bg-primary text-dark">Precio:150000</div>
                                            <input type="checkbox">
                                            </div>
                                          </div>
                             </td>
                             <td style="text-align:center">
                                    <div class="card" style="width: 19rem;">
                                            <img src="guayos3.jpg" class="rounded-pill">
                                            <div class="card-body">
                                                    <div class="p-3 mb-2 bg-primary text-dark">Precio:200000</div>
                                            <input type="checkbox">
                                            </div>
                                    </div>
                            </td>
                            <td style="text-align:center">
                                    <div class="card" style="width: 19rem;">
                                            <img src="guayos4.jpg" class="rounded-pill">
                                            <div class="card-body">
                                                    <div class="p-3 mb-2 bg-primary text-dark">Precio:200000</div>
                                            <input type="checkbox">
                                            </div>
                                     </div>
                             </td>
                             <td style="text-align:center">
                             <div class="card" style="width: 19rem;">
                                    <img src="guayos5.jpg" class="rounded-pill">
                                    <div class="card-body">
                                          <div class="p-3 mb-2 bg-primary text-dark">Precio:250000</div>
                                    <input type="checkbox">
                                    </div>
                                  </div>
                             </td>
                             <td style="text-align:center">
                                    <div class="card" style="width: 19rem;">
                                            <img src="guayos6.jpg"class=card-img-top" class="rounded-pill">
                                            <div class="card-body">
                                            <div class="p-3 mb-2 bg-primary text-dark">Precio:150000</div>
                                            <input type="checkbox">
                                            </div>
                                          </div>
                             </td>
                        </tr>
                        <tr>
                            <td colspan="6" style="text-align:center">
                                    <div class="p-3 mb-2 bg-warning text-dark"><h2>INFORMACION DE LA VENTA</h2></div>
                            </td>
                        </tr>
                        <tr>
                            <td colspan="2" style="text-align:center"><h3>Fecha de compra</h3></td>
                            <td colspan="4" style="text-align:center"><h3>Metodo de pago</h3></td>
                            
                        </tr>
                        <tr>
                            <td colspan="2" style="text-align:center">
                                <input type="date">
                            </td>
                            <td colspan="4" style="text-align:center">
                                    <div class="form-check form-check-inline">
                                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="option1">
                                            <label class="form-check-label" for="inlineRadio1"><h2>EFECTIVO</h2></label>
                                          </div>
                                          <div class="form-check form-check-inline">
                                            <input class="form-check-input" type="radio"  name="inlineRadioOptions" id="inlineRadio2" value="option2">
                                            <label class="form-check-label" for="inlineRadio2"><h2>TARJETA DEBITO</h2></label>
                                          </div>
                                          <div class="form-check form-check-inline">
                                            <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio3" value="option3">
                                            <label class="form-check-label" for="inlineRadio3"><h2>BONO EMPRESARIAL</h2></label>
                                          </div>

                            </td>
                        </tr>
                        <tr>
                            <td colspan="6" style="text-align:center">
                                    <input class="btn btn-success btn-lg btn-block" type="submit" value="CONFIRMAR COMPRA">
                                    <input class="btn btn-danger btn-lg btn-block" type="reset" value="CANCELAR COMPRA">
                            </td>
                        </tr>
                        </tr>
            </table>

        </form>
        </div>
        
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </body>
</html>
