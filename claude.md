class MyUser
  def show
    user_id = params[:user_id]
    u = User.find_by_id(user_id)
    render json: u.to_json
  end
end

#my_user_pass=dolphin1

