# Week-1---3-Programming
Week 1 - 3 Programming Code


//Ryan Bain
//ITD-1253-60498
//10-11-2022

using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace _60498LabProject
{
    public partial class Bain : Form
    {
       

        public Bain()
        {
            InitializeComponent();
        }

        private void Lbl1_Click(object sender, EventArgs e)
        {
            label1.Text = "";  
            
        }

        private void Btn4_Click(object sender, EventArgs e)
        {
            label1.BackColor = button4.BackColor;  //This will turn the label into the Red color
        }

        private void Btn2_Click(object sender, EventArgs e)
        {
            label1.BackColor = button2.BackColor;  //This will turn the label into the blue/silver color
        }

        private void Digit9_Click(object sender, EventArgs e)
        {
            label1.Text = button18.Text; //This will input the number 9 into the label
        }

        private void Clear_Click(object sender, EventArgs e)
        {
            label1.Text = "";  //This will reset the label back to default 
            
            
        }

        private void Exit_Click(object sender, EventArgs e)
        {
            this.Close();  //This will close the application
        }

        private void Btn1_Click(object sender, EventArgs e)
        {
            label1.BackColor = button1.BackColor; //This will change the label to the Maroon color
        }

        private void Btn3_Click(object sender, EventArgs e)
        {
            label1.BackColor = button3.BackColor; //This will change the label to the Blue color
        }

        private void Btn5_Click(object sender, EventArgs e)
        {
            label1.BackColor = button5.BackColor; //This will change the label to the Grey color
        }

        private void Btn6_Click(object sender, EventArgs e)
        {
            label1.BackColor = button6.BackColor; //This will change the label to the light pink color
        }

        private void Btn7_Click(object sender, EventArgs e)
        {
            label1.BackColor = button7.BackColor; //This will change the label to the Orange color
        }

        private void Btn8_Click(object sender, EventArgs e)
        {
            label1.BackColor = button8.BackColor; //This will change the label to the aqua color
        }

        private void Btn9_Click(object sender, EventArgs e)
        {
            label1.BackColor = button9.BackColor; //This will change the label to the purple color
        }

        private void Digit1_Click(object sender, EventArgs e)
        {
            label1.Text = button10.Text; //This will input the number 1 into the label
        }

        private void Digit2_Click(object sender, EventArgs e)
        {
            label1.Text = button11.Text; //This will input the number 2 into the label
        }

        private void Digit3_Click(object sender, EventArgs e)
        {
            label1.Text = button12.Text; //This will input the number 3 into the label
        }

        private void Digit4_Click(object sender, EventArgs e)
        {
            label1.Text = button13.Text; //This will input the number 4 into the label
        }

        private void Digit5_Click(object sender, EventArgs e)
        {
            label1.Text = button14.Text; //This will input the number 5 into the label
        }

        private void Digit6_Click(object sender, EventArgs e)
        {
            label1.Text = button15.Text; //This will input the number 6 into the label
        }

        private void Digit7_Click(object sender, EventArgs e)
        {
            label1.Text = button16.Text; //This will input the number 7 into the label
        }

        private void Digit8_Click(object sender, EventArgs e)
        {
            label1.Text = button17.Text; //This will input the number 8 into the label
        }
    }
}
