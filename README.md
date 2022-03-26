# paddle-set-up({Paddle.Setup({
vendor: 5358,
  eventCallback: function(data) {
    // The data.event will specify the event type
    if (data.event === "Checkout.Complete") {
      console.log(data.eventData); // Data specifics on the event
    }
    else if (data.event === "Checkout.Close") {
      console.log(data.eventData); // Data specifics on the event
    }
  }
});
