<%= form_tag root_path do %>
  <%= label_tag :product %>
  <%= text_field_tag :product %>

  <%= submit_tag 'add to cart' %>
<% end %>

<%= cart.each do |product| %>
  <p><%= product %></p>
<% end %>
