#Пример кода программы
        private void btMaunWindow_Click(object sender, RoutedEventArgs e)
        {
            WorkerProfile mainWindow = new WorkerProfile();
            mainWindow.Show();
            Visibility = Visibility.Collapsed;
        }
 private void Window_Loaded(object sender, RoutedEventArgs e)
        {
            QR = DBConnection.qrPost;
            dgFill(QR);

            statisticFill();
        }

(c) Ляпина Мария, 2020
