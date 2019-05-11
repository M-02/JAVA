package jisuan;

import java.awt.BorderLayout;
import java.awt.GridLayout;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.JTextField;
 
public class JiSuan extends JFrame{
	/**
	 * 
	 */
	private static final long serialVersionUID = 4147583030519686140L;
	/**
	 * 
	 */
	static String str="";
	static int c=0,s=0;
	static int flag=0;
	static double b=0.0;
	static double g=0.0;
	static double f=0.0;
	public static double calculater() {
		switch(c) {
		case 0:f=g;break;
		case 1:f=b+g;break;
		case 2:f=b-g;break;
		case 3:f=b*g;break;
		case 4:f=b/g;break;
		case 5:f=b%g;break;
		}
		b=f;
		c=0;
		return f;
	}
	
	JPanel panel;
	JTextField jtf;
	public JButton jb0,jb1,jb2,jb3,jb4,jb5,jb6,jb7,jb8,jb9;	//0~9四个数字（可写成数组）
	public JButton dian,jia,jian,chen,chu,den,yu,AC,CE,space2;	//加减乘除以及小数点符号
	public JiSuan(){
		this.setBounds(300, 200, 220, 220);	//窗体大小
		this.setTitle("计算器 bate 0.4");	//窗体名称
		this.setLayout(new BorderLayout());	//设置计算机窗体的布局方式
		
		jtf = new JTextField(30);		//计算区域
		
		//新建数字按钮
		jb0 = new JButton("0");
		jb1 = new JButton("1");
		jb2 = new JButton("2");
		jb3 = new JButton("3");
		jb4 = new JButton("4");
		jb5 = new JButton("5");
		jb6 = new JButton("6");
		jb7 = new JButton("7");
		jb8 = new JButton("8");
		jb9 = new JButton("9");
		
		//新建符号按钮
		dian = new JButton(".");
		jia  = new JButton("+");
		jian = new JButton("-");
		chen = new JButton("*");
		chu  = new JButton("/");
		den  = new JButton("=");
		yu   = new JButton("%");
		AC   = new JButton("←");
		CE   = new JButton("CE");
		space2=new JButton(  );
		//新建计算器数字及符号所在区域面板
		panel = new JPanel();
		panel.setLayout(new GridLayout(5,5));	//设置面板的布局方式
		
		//将各按钮组件放入面板（panel）中
		//第一行
		panel.add(CE);
		panel.add(AC);
		panel.add(yu);
		panel.add(chu);
		
		//第二行
		panel.add(jb7);
		panel.add(jb8);
		panel.add(jb9);
		panel.add(chen);
		//第三行
		panel.add(jb4);
		panel.add(jb5);
		panel.add(jb6);
		panel.add(jian);
		//第四行
		panel.add(jb1);
		panel.add(jb2);
		panel.add(jb3);
		panel.add(jia);
		//第五行
		panel.add(space2);
		panel.add(dian);
		panel.add(jb0);
		panel.add(den);
		
		this.add(jtf,BorderLayout.NORTH);
		this.add(panel);

		
		jb0.addActionListener(new ActionListener() { 

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=0;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=0;
					jtf.setText(str);

				}
			}
			
		});
		
		jb1.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=1;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=1;
					jtf.setText(str);
				}
			}
			
		});
		
		jb2.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=2;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=2;
					jtf.setText(str);
				}
			}
			
		});
		
		jb3.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=3;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=3;
					jtf.setText(str);
				}
			}
			
		});
		
		jb4.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=4;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=4;
					jtf.setText(str);
				}
			}
			
		});
		
		jb5.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=5;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=5;
					jtf.setText(str);
				}
			}
			
		});
		
		jb6.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=6;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=6;
					jtf.setText(str);
				}
			}
			
		});
		
		jb7.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=7;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=7;
					jtf.setText(str);
				}
			}
			
		});
		
		jb8.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=8;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=8;
					jtf.setText(str);
				}
			}
			
		});
		
		jb9.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(flag==1) {
					str="";
					str+=9;
					jtf.setText(str);
					flag=0;
				}
				else {
					str+=9;
					jtf.setText(str);
				}
			}
			
		});
		
		jia.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(str!="") {
					if(c==1||c==2||c==3||c==4) {
						c=0;
					}else
						g=Double.parseDouble(str);
					calculater();
					str=""+f;
					jtf.setText(str);
					c=1;
					flag=1;
					s=0;
				}
				
			}
			
		});
		
		
		jian.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(str!="") {
					if(c==1||c==2||c==3||c==4) {
						c=0;
					}else
						g=Double.parseDouble(str);
					calculater();
					str=""+f;
					jtf.setText(str);
					c=2;
					flag=1;
					s=0;
				}
				
			}
			
		});
		
		
		chen.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(str!="") {
					if(c==1||c==2||c==3||c==4) {
						c=0;
					}else
						g=Double.parseDouble(str);
					calculater();
					str=""+f;
					jtf.setText(str);
					c=3;
					flag=1;
					s=0;
				}
				
			}
			
		});
		
		
		chu.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
				if(str!="") {
					if(c==1||c==2||c==3||c==4) {
						c=0;
					}else
						g=Double.parseDouble(str);
					calculater();
					str=""+f;
					jtf.setText(str);
					c=4;
					flag=1;
					s=0;
				}
				
			}
			
		});
		
		 yu.addActionListener(new ActionListener(){

				@Override
				public void actionPerformed(ActionEvent e) {
					// TODO Auto-generated method stub
					if(str!="") {
						if(c==1||c==2||c==3||c==4) {
							c=0;
						}else
							g=Double.parseDouble(str);
						calculater();
						str=""+f;
						jtf.setText(str);
						c=5;
						flag=1;
						s=0;
				}
				}
			
		    });
		 
		 
		 
		 dian.addActionListener(new ActionListener() {

				@Override
				public void actionPerformed(ActionEvent e) {
					// TODO 自动生成的方法存根
				while(s==0) 
				{	if(flag==1) {
						str="";
						str+=".";
						g=Double.parseDouble(str);
						jtf.setText(str);
						flag=0;
						s++;
					}
					else {
						str+=".";
						jtf.setText(str);
						s++;
					}
				
			}
				}
			});
		 
		 
		 CE.addActionListener(new ActionListener(){

				@Override
				public void actionPerformed(ActionEvent e) {
					// TODO Auto-generated method stub
					
					b=c=0;
					f=flag=0;
					str="";
					jtf.setText(str);
					s=0;		
							
					}
						
					
				
			
		    });
			
		    AC.addActionListener(new ActionListener(){

				@Override
				public void actionPerformed(ActionEvent e) {
					// TODO Auto-generated method stub
					//if(str!=null){
						if(str.length()!=0){
						//	if(str!="")
							f=b%10;
							b-=f;
							str= str.substring(0,str.length()- 1);
							jtf.setText("");
							jtf.setText(str);
							}
							else if(str.length()!=0){
								//if(str!="")
								f=g%10;
								b-=f;
								str= str.substring(0,str.length()- 1);
								jtf.setText("");
								jtf.setText(str);	
					
					}
		//		}
				
				}
		    });
		 
		den.addActionListener(new ActionListener() {

			@Override
			public void actionPerformed(ActionEvent e) {
				// TODO 自动生成的方法存根
					if(str!=""&c!=1||c!=2||c!=3||c!=4||c!=5) {
						g=Double.parseDouble(str);
						calculater();
				        str=""+f;
						jtf.setText(str);
						flag=1;
						s=0;
				
					
				}
				
			}
			
		});
		
		
		this.setVisible(true);	//设置窗体显示
		this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);	//设置窗体可关闭
	}
	
	
	
	//主函数
	public static void main(String[] args) {
		new JiSuan();
		
	}
 
}
