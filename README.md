# listbox-combobox
 
using System;
using System.Windows.Forms;

namespace WindowsFormsApplication1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void cmbselect_SelectedIndexChanged(object sender, EventArgs e)
        {
            lB1.Items.Clear();
            if (cmbselect.SelectedItem == "India")
            {
                lB1.Items.Add("maharastra");
                lB1.Items.Add("gujrat");
                lB1.Items.Add("up");
            }
            if (cmbselect.SelectedItem == "USA")
            {
                lB1.Items.Add("A");
                lB1.Items.Add("B");
                lB1.Items.Add("C");
            }
        }
    }
}

        

