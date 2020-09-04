# PruebaAmChart Javascript
Prueba librería AmChart, se replica plantilla realizadas en chartjs

# Modificación de la marca AmCharts:
Se debe modificar la función e, del archivo core.sj, por:

function e() {
                    var e = t.call(this) || this;
                    e.className = "", e.valign = "";
                    var i = .3;
                    var n = Object(ie.c)("#474758");
                    var r = new Rt.a;
                    var a = r, o = e.createChild(K.a);
                    o.shouldClone = !1, o.isMeasured = !1, o.segments = [[{x: 15, y: 15}, {x: 27, y: 15}, {
                        x: 36,
                        y: 6
                    }, {x: 40.5, y: 10.5}, {x: 45, y: 6}, {x: 54, y: 15}, {
                        x: 60,
                        y: 15
                    }]];
                    var s = e.createChild(K.a);
                    var u = new Gt.a;
                    var h = e.states.create("");
                    return
                }
