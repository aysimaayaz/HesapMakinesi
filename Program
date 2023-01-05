using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace hesapmakinesi
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }
        char islem;
        private void button1_Click(object sender, EventArgs e)
        {
            Button btn = sender as Button;
            textBox1.Text += btn.Text;
          
        }

        private void button13_Click(object sender, EventArgs e)
        {
            Button btnislem = sender as Button;
            islem = Convert.ToChar( btnislem.Text);
            label1.Text = textBox1.Text;
            textBox1.Clear();
            

        }

        private void button12_Click(object sender, EventArgs e)
        {
            double sonuc;
            switch (islem)
            {
                case '-':
                    sonuc = Convert.ToDouble(label1.Text) - Convert.ToDouble(textBox1.Text);
                    textBox1.Text = sonuc.ToString();
                    break;
                case '*':
                    sonuc = Convert.ToDouble(label1.Text) * Convert.ToDouble(textBox1.Text);
                    textBox1.Text = sonuc.ToString();
                    break;
                case '+':
                    sonuc = Convert.ToDouble(label1.Text) + Convert.ToDouble(textBox1.Text);
                    textBox1.Text = sonuc.ToString();
                    break;
                case '/':
                    sonuc = Convert.ToDouble(label1.Text) / Convert.ToDouble(textBox1.Text);
                    textBox1.Text = sonuc.ToString();
                    break;

                default:
                    break;
            }
        }

        private void button17_Click(object sender, EventArgs e)
        {
            textBox1.Clear();
            label1.Text = "";
        }

        private void button18_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text.Substring(0,textBox1.Text.Length-1); 
        }
    }
}
