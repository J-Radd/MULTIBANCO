# MULTIBANCO
1stripe.createSource({
  type: 'multibanco',
  amount: 1099,
  currency: 'eur',
  owner: {
    name: 'Jenny Rosen',
    email: 'jenny.rosen@example.com',
  },
  redirect: {
    return_url: 'https://shop.example.com/crtA6B28E1',
  },
}).then(function(result) {
  // handle result.error or result.source
});
