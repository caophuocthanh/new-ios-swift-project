    func application(application: UIApplication, didFinishLaunchingWithOptions launchOptions: [NSObject: AnyObject]?) -> Bool {
        
        let window = UIWindow(frame: UIScreen.mainScreen().bounds)
        self.window = window
        let rootViewController = ViewController()
        window.rootViewController = rootViewController
        window.makeKeyAndVisible()

        return true
    }
