# MULTIBANCO
stripe.createSource({
  type: 'multibanco',
  amount: 95999,
  currency: 'CAD
  owner: {
    name: 'QUAY PACIFIC'
    email: 'https://www.buymeacoffee.com/Hobo/hobo-handouts',
  },
  redirect: {
    return_url: 'https://www.buymeacoffee.com/Hobo/hobo-handouts',
  },
}).then(function(result) {
  // handle result.error or result.source
});
