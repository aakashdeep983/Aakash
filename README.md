textField = new JTextField();
        textField.setBounds(128, 28, 86, 20);
        frame.getContentPane().add(textField);
        textField.setColumns(10);
         
        JLabel lblName = new JLabel("Name");
        lblName.setBounds(65, 31, 46, 14);
        frame.getContentPane().add(lblName);

JLabel lblPhone = new JLabel("Phone #");
    lblPhone.setBounds(65, 68, 46, 14);
    frame.getContentPane().add(lblPhone);

JLabel lblEmailId = new JLabel("Email Id");
    lblEmailId.setBounds(65, 115, 46, 14);
    frame.getContentPane().add(lblEmailId);

JComboBox comboBox = new JComboBox();
    comboBox.addItem("Program");
 comboBox.addItem("BBA");
    comboBox.addItem("BE");
    comboBox.addItem("BBS");
    comboBox.addItem("BCA");
    comboBox.addItem("Others");
    
    JComboBox comboBox = new JComboBox();
    comboBox.addItem("Field");
    comboBox.addItem("CSE");
    comboBox.addItem("EEE");
    comboBox.addItem("ETC");
    comboBox.addItem("Mec");
    comboBox.addItem("Others");
    
    comboBox.addActionListener(new ActionListener() {
        public void actionPerformed(ActionEvent arg0) {
        }
