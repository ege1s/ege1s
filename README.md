- 👋 Hi, I’m @ege1s
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ege1s/ege1s is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

        private void button1_Click(object sender, EventArgs e)
        {
            {
                int etiketFiyati;
                double indirimliFiyat;
                etiketFiyati = Convert.ToInt32(textBox1.Text);
                indirimliFiyat = etiketFiyati - etiketFiyati * 0.10; 
                label3.Text = indirimliFiyat.ToString();
            }
        }

        private void button2_Click(object sender, EventArgs e)
        {
            {
                int etiketFiyati;
                double indirimliFiyat;
                etiketFiyati = Convert.ToInt32(textBox1.Text);
                indirimliFiyat = etiketFiyati - etiketFiyati * 0.25; 
                label3.Text = indirimliFiyat.ToString();
            }
        }

        private void button4_Click_1(object sender, EventArgs e)
        {
            {
                int etiketFiyati;
                double indirimliFiyat;
                etiketFiyati = Convert.ToInt32(textBox1.Text);
                indirimliFiyat = etiketFiyati - etiketFiyati * 0.50; 
                label3.Text = indirimliFiyat.ToString();
            }
        }

        private void button3_Click(object sender, EventArgs e)
        {
            {
                int etiketFiyati;
                double indirimliFiyat;
                etiketFiyati = Convert.ToInt32(textBox1.Text);
                indirimliFiyat = etiketFiyati - etiketFiyati * 0.75; 
                label3.Text = indirimliFiyat.ToString();
            }

        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void button4_Click_2(object sender, EventArgs e)
        {
            {
                int etiketFiyati;
                double indirimliFiyat;
                etiketFiyati = Convert.ToInt32(textBox1.Text);
                indirimliFiyat = etiketFiyati - etiketFiyati * 0.75; //Yüzde 75 indirim
                label3.Text = indirimliFiyat.ToString();
            }

        }
    }
}
