# URL-Encoder
URl Encoder for .NET 4 Windows Form

Simples Usage Exemple:

                using System;
                using System.Windows.Forms;
                using URL_Encoder;

                namespace WhatsappAPI_Creator
                {
                 public partial class Form1 : Form
                 {
                  public Form1()
                  {
                   InitializeComponent();
                  }

                  private void btnEncode_Click(object sender, EventArgs e)
                  {
                  string TextEncoder = TextToEncode.Text;
                  var output = TextEncoder.UrlEncode();
                  EncodedText.Text = output;
                  }
                 }
                }
               }
