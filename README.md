# Segenda-loginpass-swift
//
//  ViewController.swift
//  Segenda
//
//  Created by macbook on 5/16/19.
//  Copyright © 2019 molnijaug. All rights reserved.
//

import UIKit



class ViewController: UIViewController {

    @IBOutlet weak var theLogin: UITextField!
    @IBOutlet weak var thePassword: UITextField!
    @IBOutlet weak var theExitText: UILabel!
    
    @IBAction func theKey(_ sender: Any)
    {
        let logintext = "s"
        let passtext = "s"
    if theLogin.text == logintext &&
    thePassword.text == passtext
        
    {
        theExitText.text = "Ваши данные верны!"
        theExitText.backgroundColor=UIColor.green
        }
    else
    {
        theExitText.text = "Ваши данные НЕ верны!"
        theExitText.backgroundColor=UIColor.red
        }
        
        let logintextt = "a"
        let passtextt = "a"
        if theLogin.text == logintextt &&
            thePassword.text == passtextt
            
        {
            theExitText.text = "Ваши данные верны!"
            theExitText.backgroundColor=UIColor.green
        }
        else
        {
            theExitText.text = "Ваши данные НЕ верны!"
            theExitText.backgroundColor=UIColor.red
        }
    }

    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view.
    }
    
}
    
    
    
    
    


