# Meteor no OpenShift Getup Cloud
Este quickstart permite rodar uma aplicação Meteor.js no OpenShift da Getup Cloud.

Para criar sua aplicação Meteor.js, primeiro vcê precisa registrar-se na Getup. Acesse http://getupcloud.com/#/sign-up e faça seu cadastro. Você recebe gratuitamente 750hs para testar a plataforma.

Para criar sua app, execute no terminal:

    rhc app-create meteor nodejs-0.6 mongodb-2.2 --from-code https://github.com/caruccio/openshift-meteorjs-quickstart.git
    
Acesse a URL [http://meteor-$namespace.getup.io](#) e siga as instruções para publicar seu código.
