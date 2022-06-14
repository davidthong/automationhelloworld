node() {

    
                
                println("branch to build = " + params.Branch_To_Build)
                
                def response = httpRequest acceptType: 'APPLICATION_JSON', 
                httpMode: 'GET', ignoreSslErrors: true, authentication: 'tryAgain',
                url: 'https://aap/api/v2/job_templates/9/launch/'
                
                println("Response is = " + response.content)
                
                body = """ {"limit": "localhost"}  """
                
                println(body)
                response = httpRequest acceptType: 'APPLICATION_JSON', 
                httpMode: 'POST', ignoreSslErrors: true, authentication: 'tryAgain',
                
                url: 'https://aap/api/v2/job_templates/9/launch/'
                
                
            
        
    
}
