Test Case 1:Automation Test Case 1: Automation to add owner using Katalon with Owner admin

WebUI.openBrowser('')

WebUI.navigateToUrl('http://admin:admin@clinic.doveryai-no-proveryai.com:9966/petclinic/swagger-ui.html"')

WebUI.navigateToUrl('https://clinic.doveryai-no-proveryai.com/petclinic/')

WebUI.click(findTestObject('Object Repository/Page_SpringPetclinicAngular/a_Owners'))

WebUI.click(findTestObject('Object Repository/Page_SpringPetclinicAngular/span_Add New'))

WebUI.setText(findTestObject('Object Repository/Page_SpringPetclinicAngular/input_First Name_firstName'), 'Mike ')

WebUI.setText(findTestObject('Object Repository/Page_SpringPetclinicAngular/input_Last Name_lastName'), 'Dean')

WebUI.setText(findTestObject('Object Repository/Page_SpringPetclinicAngular/input_Address_address'), '1234 Wall Street')

WebUI.setText(findTestObject('Object Repository/Page_SpringPetclinicAngular/input_City_city'), 'Austin')

WebUI.setText(findTestObject('Object Repository/Page_SpringPetclinicAngular/input_Telephone_telephone'), '1234567890')

WebUI.click(findTestObject('Object Repository/Page_SpringPetclinicAngular/button_Add Owner'))

WebUI.closeBrowser()


Test Case 2: Automation to add Pet Type using Katalon Studio with Vet admin

WebUI.openBrowser('')

WebUI.navigateToUrl('http://vet_admin:admin@clinic.doveryai-no-proveryai.com:9966/petclinic/swagger-ui.html')

WebUI.navigateToUrl('https://clinic.doveryai-no-proveryai.com/petclinic/')

WebUI.click(findTestObject('Object Repository/span_Pet Types'))

WebUI.click(findTestObject('Object Repository/button_Add'))

WebUI.setText(findTestObject('Object Repository/input_Name_name'), 'Rhino')

WebUI.click(findTestObject('Object Repository/button_Save'))

WebUI.closeBrowser()


