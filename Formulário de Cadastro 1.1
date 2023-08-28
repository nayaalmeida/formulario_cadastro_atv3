# formulario_cadastro_atv3
import 'package:flutter/material.dart';

class HomePage extends StatefulWidget {
  const HomePage({super.key});

  @override
  State<HomePage> createState() => _HomePageState();
}

//-----------------------------------------------------------------------
class _HomePageState extends State<HomePage> {
  DateTime dataSelecionada = DateTime.now();
  String? _nomeCompleto, _cpf, _endereco, _complemento, _numero;

  bool _opEletronica = false;
  bool _opAutomacao = false;
  bool _opdevSistem = false;

  int selectedRadio = 0;

  String _opcaoSelecionada = "";
  List<String> _opcoes = [
    '',
    'Recife',
    'São Paulo',
    'João Pessoa',
    'Jaboatão dos Guararapes.',
  ];
//--------------------------------------------------------------------------
  Future<void> _escolherData(BuildContext context) async {
    final picked = await showDatePicker(
      context: context,
      initialDate: dataSelecionada,
      firstDate: DateTime(2000),
      lastDate: DateTime(2101),
    );
  }

//----------------------------------------------------------------------------
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Container(
        padding: EdgeInsets.all(50),
        child: Center(
          child: Column(
            mainAxisAlignment: MainAxisAlignment.spaceBetween,
            children: [
              Text(
                "Formulário de Cadastro",
                style: TextStyle(
                  fontSize: 45,
                  fontWeight: FontWeight.w900,
                  color: Colors.blue,
                ),
              ),
              //-------------------------------------------------------------------------------
              Row(
                children: [
                  Expanded(
                    flex: 2,
                    child: TextFormField(
                      onChanged: (value) {
                        _nomeCompleto = value;
                      },
                      decoration: InputDecoration(
                        labelText: "Nome Completo",
                        border: OutlineInputBorder(),
                        prefixIcon: Icon(Icons.abc),
                      ),
                    ),
                  ),
                  SizedBox(
                    width: 30,
                  ),
                ],
              ),
              //--------------------------------------------------------------------------
              Row(
                children: [
                  Expanded(
                    flex: 4,
                    child: TextFormField(
                      onChanged: (value) {
                        _cpf = value;
                      },
                      decoration: InputDecoration(
                        labelText: "CPF",
                        border: OutlineInputBorder(),
                        prefixIcon: Icon(Icons.person),
                      ),
                      maxLines: 1,
                    ),
                  ),
                  //-----------------------------------------------------------------------
                  SizedBox(
                    width: 30,
                  ),
                  Expanded(
                    flex: 3,
                    child: Row(
                      mainAxisAlignment: MainAxisAlignment.spaceEvenly,
                      children: [
                        Text("${dataSelecionada.toLocal()}".split(' ')[0]),
                        ElevatedButton(
                          onPressed: () => _escolherData(context),
                          child: Text("Data de Nascimento"),
                        ),
                      ],
                    ),
                  ),
                ],
              ),
              //-----------------------------------------------------------------------
              Row(
                children: [
                  Text("Escolha a(s) áreas de interesse:"),
                  SizedBox(
                    width: 30,
                  ),
                  Text("Escolha o dia de vencimento:"),
                  SizedBox(
                    width: 30,
                  ),
                ],
              ),
              //-----------------------------------------------------------------------
              Row(
                children: [
                  Expanded(
                    child: Column(
                      crossAxisAlignment: CrossAxisAlignment.start,
                      children: [
                        CheckboxListTile(
                          controlAffinity: ListTileControlAffinity.leading,
                          value: _opEletronica,
                          onChanged: (bool? newValue) {
                            setState(() {
                              _opEletronica = newValue!;
                            });
                          },
                          title: Text('Eletrônica'),
                        ),
                        CheckboxListTile(
                          controlAffinity: ListTileControlAffinity.leading,
                          value: _opAutomacao,
                          onChanged: (bool? newValue) {
                            setState(() {
                              _opAutomacao = newValue!;
                            });
                          },
                          title: Text('Automação'),
                        ),
                        CheckboxListTile(
                          controlAffinity: ListTileControlAffinity.leading,
                          value: _opdevSistem,
                          onChanged: (bool? newValue) {
                            setState(() {
                              _opdevSistem = newValue!;
                            });
                          },
                          title: Text('Desenvolvimento de Sistemas'),
                        ),
                      ],
                    ),
                  ),
                  //------------------------------------------------------------------------------
                  Expanded(
                    child: Column(
                      crossAxisAlignment: CrossAxisAlignment.start,
                      children: [
                        RadioListTile(
                          value: 1,
                          groupValue: selectedRadio,
                          onChanged: (int? value) {
                            setState(() {
                              selectedRadio = value!;
                            });
                          },
                          title: Text('5'),
                        ),
                        RadioListTile(
                          value: 2,
                          groupValue: selectedRadio,
                          onChanged: (int? value) {
                            setState(() {
                              selectedRadio = value!;
                            });
                          },
                          title: Text('10'),
                        ),
                        RadioListTile(
                          value: 3,
                          groupValue: selectedRadio,
                          onChanged: (int? value) {
                            setState(() {
                              selectedRadio = value!;
                            });
                          },
                          title: Text('15'),
                        ),
                      ],
                    ),
                  ),
                ],
              ),
              //-----------------------------------------------------------------------------
              Row(
                children: [
                  Expanded(
                    flex: 7,
                    child: TextFormField(
                      onChanged: (value) {
                        _endereco = value;
                      },
                      decoration: InputDecoration(
                        labelText: "Endereço",
                        border: OutlineInputBorder(),
                        prefixIcon: Icon(Icons.location_on),
                      ),
                    ),
                  ),
                  SizedBox(
                    width: 30,
                  ),
                ],
              ),
              //----------------------------------------------------------------------------------
              Row(
                mainAxisAlignment: MainAxisAlignment.spaceBetween,
                children: [
                  Expanded(
                    flex: 2,
                    child: TextFormField(
                      onChanged: (value) {
                        _numero = value;
                      },
                      decoration: InputDecoration(
                        labelText: "N°",
                        border: OutlineInputBorder(),
                        prefixIcon: Icon(Icons.map),
                      ),
                    ),
                  ),
                  //--------------------------------------------------------------------------------
                  SizedBox(
                    width: 30,
                  ),
                  Expanded(
                    flex: 4,
                    child: DropdownButtonFormField<String>(
                      value: _opcaoSelecionada,
                      onChanged: (novoValor) {
                        setState(() {
                          _opcaoSelecionada = novoValor!;
                        });
                      },
                      items: _opcoes.map((opcao) {
                        return DropdownMenuItem<String>(
                          value: opcao,
                          child: Text(opcao),
                        );
                      }).toList(),
                      decoration: InputDecoration(
                        border: OutlineInputBorder(),
                        labelText: 'Cidade',
                      ),
                    ),
                  ),
                ],
              ),
              //-------------------------------------------------------------------------------
              SizedBox(
                child: TextFormField(
                  onChanged: (value) => _complemento = value,
                  maxLines: 5,
                  decoration: InputDecoration(
                    label: Text("Complemento"),
                    border: OutlineInputBorder(),
                    prefixIcon: Icon(Icons.more),
                  ),
                ),
              ),

              //-------------------------------------------------------------------------------
              SizedBox(
                width: double.infinity,
                height: 30,
                child: ElevatedButton.icon(
                  onPressed: () {
                    print("$_nomeCompleto $_cpf $_endereco $_numero");
                    print("$_opcaoSelecionada $dataSelecionada");
                  },
                  icon: Icon(Icons.save),
                  label: Text("Cadastrar"),
                ),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
