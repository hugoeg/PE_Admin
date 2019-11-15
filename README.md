# PE_Adminpackage view
import java.awt.BorderLayout;
import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.border.EmptyBorder;
import java.awt.Window.Type;
import javax.swing.border.LineBorder;
import java.awt.Color;
import javax.swing.border.TitledBorder;
import javax.swing.border.EtchedBorder;
import javax.swing.JLabel;
import java.awt.Font;
import javax.swing.JTextField;
import javax.swing.JCheckBox;
import com.jgoodies.forms.factories.DefaultComponentFactory;

public class Tela extends JFrame {

	private JPanel contentPane;
	private JTextField tfnome;
	private JTextField data;
	private JTextField número;
	private JTextField tfestadoip;
	private JTextField textField_3;
	private JTextField tfescolaridade;
	private JTextField tftelefonefixo;
	private JTextField tftelefonecelular;
	private JTextField tfemail;
	private JTextField tfwhatssapp;
	private JTextField tfrua;
	private JTextField tfbairro;
	private JTextField tfnúmero;
	private JTextField tfcidade;
	private JTextField tfcep;
	private JTextField tfestadoir;
	private JTextField tfcasa;
	private JTextField tfmaterial;
	private JTextField tfcomodo;
	private JTextField tfesgoto;
	private JTextField tfasfalto;
	private JTextField tfprofissão;
	private JTextField tfsituaçãoeconomica;
	private JTextField tfagua;
	private JTextField tfenergia;
	private JTextField tfgas;
	private JTextField tftelefone;
	private JTextField tfalimentação;
	private JTextField tftransporte;
	private JTextField tfmoradia;
	private JTextField tfmedicamentos;
	private JTextField tftotal;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Tela frame = new Tela();
					frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the frame.
	 */
	public Tela() {
		setTitle("Cadastro de Benefici\u00E1rio");
		setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		setBounds(100, 100, 493, 700);
		contentPane = new JPanel();
		contentPane.setToolTipText("");
		contentPane.setBorder(new EmptyBorder(5, 5, 5, 5));
		setContentPane(contentPane);
		contentPane.setLayout(null);
		
		JPanel panel = new JPanel();
		panel.setForeground(new Color(0, 0, 0));
		panel.setBorder(new TitledBorder(new EtchedBorder(EtchedBorder.LOWERED, new Color(255, 255, 255), new Color(160, 160, 160)), "Informa\u00E7\u00F5es Pessoais", TitledBorder.LEFT, TitledBorder.TOP, null, new Color(0, 0, 0)));
		panel.setToolTipText("Informa\u00E7\u00F5es Pessoais");
		panel.setBounds(0, 11, 240, 202);
		contentPane.add(panel);
		panel.setLayout(null);
		
		JLabel lblNewLabel = new JLabel("Nome:");
		lblNewLabel.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblNewLabel.setBounds(10, 22, 48, 14);
		panel.add(lblNewLabel);
		
		tfnome = new JTextField();
		tfnome.setBounds(54, 19, 176, 20);
		panel.add(tfnome);
		tfnome.setColumns(10);
		
		JLabel lblDataDeNascimento = new JLabel("Data de Nascimento:");
		lblDataDeNascimento.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblDataDeNascimento.setLabelFor(this);
		lblDataDeNascimento.setBounds(10, 47, 120, 14);
		panel.add(lblDataDeNascimento);
		
		data = new JTextField();
		data.setBounds(140, 44, 89, 20);
		panel.add(data);
		data.setColumns(10);
		
		JLabel lblRg = new JLabel("RG:");
		lblRg.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblRg.setBounds(10, 72, 48, 14);
		panel.add(lblRg);
		
		número = new JTextField();
		número.setBounds(34, 69, 96, 20);
		panel.add(número);
		número.setColumns(10);
		
		JLabel lblUf = new JLabel("UF:");
		lblUf.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblUf.setBounds(134, 72, 24, 14);
		panel.add(lblUf);
		
		tfestadoip = new JTextField();
		tfestadoip.setBounds(161, 69, 69, 20);
		panel.add(tfestadoip);
		tfestadoip.setColumns(10);
		
		JLabel lblCpf = new JLabel("CPF");
		lblCpf.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblCpf.setBounds(10, 97, 48, 14);
		panel.add(lblCpf);
		
		textField_3 = new JTextField();
		textField_3.setBounds(34, 94, 196, 20);
		panel.add(textField_3);
		textField_3.setColumns(10);
		
		JLabel lblEscolaridade = new JLabel("Escolaridade:");
		lblEscolaridade.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblEscolaridade.setBounds(10, 122, 78, 14);
		panel.add(lblEscolaridade);
		
		tfescolaridade = new JTextField();
		tfescolaridade.setBounds(98, 119, 132, 20);
		panel.add(tfescolaridade);
		tfescolaridade.setColumns(10);
		
		JLabel lblProfisso = new JLabel("Profiss\u00E3o:");
		lblProfisso.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblProfisso.setBounds(10, 147, 62, 14);
		panel.add(lblProfisso);
		
		tfprofissão = new JTextField();
		tfprofissão.setBounds(98, 144, 132, 20);
		panel.add(tfprofissão);
		tfprofissão.setColumns(10);
		
		JLabel lblSituaoEconmica = new JLabel("Situa\u00E7\u00E3o Econ\u00F4mica:");
		lblSituaoEconmica.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblSituaoEconmica.setBounds(10, 172, 120, 14);
		panel.add(lblSituaoEconmica);
		
		tfsituaçãoeconomica = new JTextField();
		tfsituaçãoeconomica.setBounds(134, 169, 96, 20);
		panel.add(tfsituaçãoeconomica);
		tfsituaçãoeconomica.setColumns(10);
		
		JPanel panel_1 = new JPanel();
		panel_1.setBorder(new TitledBorder(new EtchedBorder(EtchedBorder.LOWERED, new Color(255, 255, 255), new Color(160, 160, 160)), "Informa\u00E7\u00F5es de Contato", TitledBorder.LEFT, TitledBorder.TOP, null, new Color(0, 0, 0)));
		panel_1.setBounds(238, 11, 240, 128);
		contentPane.add(panel_1);
		panel_1.setLayout(null);
		
		JLabel lblTelefoneFixo = new JLabel("Telefone Fixo:");
		lblTelefoneFixo.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblTelefoneFixo.setBounds(10, 22, 80, 14);
		panel_1.add(lblTelefoneFixo);
		
		tftelefonefixo = new JTextField();
		tftelefonefixo.setBounds(100, 19, 130, 20);
		panel_1.add(tftelefonefixo);
		tftelefonefixo.setColumns(10);
		
		JLabel lblTelefoneCelular = new JLabel("Telefone Cel. :");
		lblTelefoneCelular.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblTelefoneCelular.setBounds(10, 47, 100, 14);
		panel_1.add(lblTelefoneCelular);
		
		tftelefonecelular = new JTextField();
		tftelefonecelular.setBounds(100, 44, 130, 20);
		panel_1.add(tftelefonecelular);
		tftelefonecelular.setColumns(10);
		
		JLabel lblEmail = new JLabel("Email:");
		lblEmail.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblEmail.setBounds(10, 72, 48, 14);
		panel_1.add(lblEmail);
		
		tfemail = new JTextField();
		tfemail.setText("");
		tfemail.setBounds(55, 69, 175, 20);
		panel_1.add(tfemail);
		tfemail.setColumns(10);
		
		JLabel lblWatssapp = new JLabel("WhatssApp:");
		lblWatssapp.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblWatssapp.setBounds(10, 97, 68, 14);
		panel_1.add(lblWatssapp);
		
		tfwhatssapp = new JTextField();
		tfwhatssapp.setBounds(100, 94, 130, 20);
		panel_1.add(tfwhatssapp);
		tfwhatssapp.setColumns(10);
		
		JLabel label = DefaultComponentFactory.getInstance().createTitle("");
		label.setBounds(95, 414, 91, 14);
		contentPane.add(label);
		
		JPanel panel_2 = new JPanel();
		panel_2.setLayout(null);
		panel_2.setBorder(new TitledBorder(new EtchedBorder(EtchedBorder.LOWERED, new Color(255, 255, 255), new Color(160, 160, 160)), "Informa\u00E7\u00F5es Residenciais", TitledBorder.LEFT, TitledBorder.TOP, null, new Color(0, 0, 0)));
		panel_2.setBounds(0, 212, 240, 128);
		contentPane.add(panel_2);
		
		JLabel lblRua = new JLabel("Rua:");
		lblRua.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblRua.setBounds(10, 22, 80, 14);
		panel_2.add(lblRua);
		
		tfrua = new JTextField();
		tfrua.setColumns(10);
		tfrua.setBounds(55, 19, 175, 20);
		panel_2.add(tfrua);
		
		JLabel lblBairro = new JLabel("Bairro:");
		lblBairro.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblBairro.setBounds(10, 47, 100, 14);
		panel_2.add(lblBairro);
		
		tfbairro = new JTextField();
		tfbairro.setColumns(10);
		tfbairro.setBounds(55, 44, 175, 20);
		panel_2.add(tfbairro);
		
		JLabel lblN = new JLabel("N\u00BA:");
		lblN.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblN.setBounds(10, 72, 23, 14);
		panel_2.add(lblN);
		
		tfnúmero = new JTextField();
		tfnúmero.setText("");
		tfnúmero.setColumns(10);
		tfnúmero.setBounds(35, 69, 55, 20);
		panel_2.add(tfnúmero);
		
		JLabel lblCidade = new JLabel("Cidade:");
		lblCidade.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblCidade.setBounds(10, 97, 68, 14);
		panel_2.add(lblCidade);
		
		tfcidade = new JTextField();
		tfcidade.setColumns(10);
		tfcidade.setBounds(55, 94, 80, 20);
		panel_2.add(tfcidade);
		
		JLabel lblCep = new JLabel("CEP:");
		lblCep.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblCep.setBounds(95, 72, 32, 14);
		panel_2.add(lblCep);
		
		tfcep = new JTextField();
		tfcep.setBounds(130, 69, 100, 20);
		panel_2.add(tfcep);
		tfcep.setColumns(10);
		
		JLabel label_1 = new JLabel("UF:");
		label_1.setFont(new Font("Tahoma", Font.BOLD, 11));
		label_1.setBounds(140, 97, 24, 14);
		panel_2.add(label_1);
		
		tfestadoir = new JTextField();
		tfestadoir.setBounds(160, 94, 70, 20);
		panel_2.add(tfestadoir);
		tfestadoir.setColumns(10);
		
		JPanel panel_3 = new JPanel();
		panel_3.setLayout(null);
		panel_3.setBorder(new TitledBorder(new EtchedBorder(EtchedBorder.LOWERED, new Color(255, 255, 255), new Color(160, 160, 160)), "Informa\u00E7\u00E3o Habitacional", TitledBorder.LEFT, TitledBorder.TOP, null, new Color(0, 0, 0)));
		panel_3.setBounds(238, 138, 240, 128);
		contentPane.add(panel_3);
		
		JLabel lblCasa = new JLabel("Casa:");
		lblCasa.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblCasa.setBounds(10, 22, 39, 14);
		panel_3.add(lblCasa);
		
		tfcasa = new JTextField();
		tfcasa.setColumns(10);
		tfcasa.setBounds(75, 19, 155, 20);
		panel_3.add(tfcasa);
		
		JLabel lblMaterial = new JLabel("Material:");
		lblMaterial.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblMaterial.setBounds(10, 47, 51, 14);
		panel_3.add(lblMaterial);
		
		tfmaterial = new JTextField();
		tfmaterial.setColumns(10);
		tfmaterial.setBounds(75, 44, 155, 20);
		panel_3.add(tfmaterial);
		
		JLabel lblNDeComodos = new JLabel("N\u00BA de Comodos:");
		lblNDeComodos.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblNDeComodos.setBounds(10, 72, 89, 14);
		panel_3.add(lblNDeComodos);
		
		tfcomodo = new JTextField();
		tfcomodo.setText("");
		tfcomodo.setColumns(10);
		tfcomodo.setBounds(109, 69, 121, 20);
		panel_3.add(tfcomodo);
		
		JLabel lblEsgoto = new JLabel("Esgoto:");
		lblEsgoto.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblEsgoto.setBounds(10, 97, 43, 14);
		panel_3.add(lblEsgoto);
		
		tfesgoto = new JTextField();
		tfesgoto.setColumns(10);
		tfesgoto.setBounds(63, 94, 51, 20);
		panel_3.add(tfesgoto);
		
		JLabel lblAsfalto = new JLabel("Asfalto:");
		lblAsfalto.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblAsfalto.setBounds(119, 97, 48, 14);
		panel_3.add(lblAsfalto);
		
		tfasfalto = new JTextField();
		tfasfalto.setBounds(177, 94, 53, 20);
		panel_3.add(tfasfalto);
		tfasfalto.setColumns(10);
		
		JPanel panel_4 = new JPanel();
		panel_4.setLayout(null);
		panel_4.setBorder(new TitledBorder(new EtchedBorder(EtchedBorder.LOWERED, new Color(255, 255, 255), new Color(160, 160, 160)), "Despesas Familiares", TitledBorder.LEFT, TitledBorder.TOP, null, new Color(0, 0, 0)));
		panel_4.setBounds(238, 264, 240, 256);
		contentPane.add(panel_4);
		
		JLabel lblgua = new JLabel("\u00C1gua:");
		lblgua.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblgua.setBounds(10, 22, 80, 14);
		panel_4.add(lblgua);
		
		tfagua = new JTextField();
		tfagua.setColumns(10);
		tfagua.setBounds(110, 19, 120, 20);
		panel_4.add(tfagua);
		
		JLabel lblEnergia = new JLabel("Energia:");
		lblEnergia.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblEnergia.setBounds(10, 47, 100, 14);
		panel_4.add(lblEnergia);
		
		tfenergia = new JTextField();
		tfenergia.setColumns(10);
		tfenergia.setBounds(110, 44, 120, 20);
		panel_4.add(tfenergia);
		
		JLabel lblGs = new JLabel("G\u00E1s:");
		lblGs.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblGs.setBounds(10, 72, 48, 14);
		panel_4.add(lblGs);
		
		tfgas = new JTextField();
		tfgas.setText("");
		tfgas.setColumns(10);
		tfgas.setBounds(110, 69, 120, 20);
		panel_4.add(tfgas);
		
		JLabel lblTelefone = new JLabel("Telefone:");
		lblTelefone.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblTelefone.setBounds(10, 97, 68, 14);
		panel_4.add(lblTelefone);
		
		tftelefone = new JTextField();
		tftelefone.setColumns(10);
		tftelefone.setBounds(110, 94, 120, 20);
		panel_4.add(tftelefone);
		
		JLabel lblAlimentao = new JLabel("Alimenta\u00E7\u00E3o:");
		lblAlimentao.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblAlimentao.setBounds(10, 122, 100, 14);
		panel_4.add(lblAlimentao);
		
		JLabel lblTransporte = new JLabel("Transporte:");
		lblTransporte.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblTransporte.setBounds(10, 147, 100, 14);
		panel_4.add(lblTransporte);
		
		JLabel lblMoradia = new JLabel("Moradia:");
		lblMoradia.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblMoradia.setBounds(10, 172, 100, 14);
		panel_4.add(lblMoradia);
		
		JLabel lblMedicamentos = new JLabel("Medicamentos:");
		lblMedicamentos.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblMedicamentos.setBounds(10, 197, 100, 14);
		panel_4.add(lblMedicamentos);
		
		JLabel lblTotal = new JLabel("Total:");
		lblTotal.setFont(new Font("Tahoma", Font.BOLD, 11));
		lblTotal.setBounds(10, 222, 100, 14);
		panel_4.add(lblTotal);
		
		tfalimentação = new JTextField();
		tfalimentação.setColumns(10);
		tfalimentação.setBounds(110, 119, 120, 20);
		panel_4.add(tfalimentação);
		
		tftransporte = new JTextField();
		tftransporte.setColumns(10);
		tftransporte.setBounds(110, 144, 120, 20);
		panel_4.add(tftransporte);
		
		tfmoradia = new JTextField();
		tfmoradia.setColumns(10);
		tfmoradia.setBounds(110, 169, 120, 20);
		panel_4.add(tfmoradia);
		
		tfmedicamentos = new JTextField();
		tfmedicamentos.setColumns(10);
		tfmedicamentos.setBounds(110, 194, 120, 20);
		panel_4.add(tfmedicamentos);
		
		tftotal = new JTextField();
		tftotal.setColumns(10);
		tftotal.setBounds(110, 219, 120, 20);
		panel_4.add(tftotal);
	}
}
